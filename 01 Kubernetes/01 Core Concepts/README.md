# Core Architecture
- This is the highlevel overview of the each components in K8s core architecture.

## Master Node Component

- ### Master
    - Manage, Plan, Schedule and Monitor slave nodes

- ### ETCD
    - Database that stores information in a Key-Value format.

- ### Kube-Scheduler
    - Identifies the right node to place a container based on the containers resource requirements, the worker nodes capacity or any other policies & constraints such as tents and tolerations or node affinity rules.

- ### Controllers and Controller Manager

    - **Node-Controller**
        - Takes care of Nodes, responsible for onboarding new nodes to the cluster, handling situations where nodes become unavailable or gets destroyed.
        
    - **Replication Controller**
        - Ensures that desired number of containers are running all times in replication group.

- ### Kube-API Server
    - Primary management component of K8s, Responsible of orchestrating all operations within the cluster, Exposes the K8s API which is used by external users to perform management operations on cluster and Kube-API Server also perform many other works.

## Slave Node Component

- ### Kubelet
    - It's an agent runs on each node in a cluster. It listens for instructions from the kube-api server and deploys or destroys containers on the nodes as required.

- ### Kube-Proxy
    - Ensures that the necessary rules are in place on the worker nodes to allow the containers running on them to reach each other.
----
## ETCD
- It is Distributed, reliable key-value database that is simple, secure and fast.

### Key-Values Store
- Stores information in Documents or pages.
- Changing one document does not affect other.
- Easy to convert into JSON.

### ETCD Control Client
- Default Client
- It is a command line client for etcd and we can use it to store and retrive key-value pair.
- Store the value
    ```
    ./etcdctl set key1 value1
    ```
- Retrive the value
    ```
    ./etcdctl get key1
    ```

### ETCD Role in K8s
- Stores information regarding The Clusters, Such as nodes, pods, configs, secrets, accounts, roles, bindings and others.
- Every additional changes and information such as adding nodes, deploying pods or replica sets are updated in etcd server.
- Default port on which etcd listens is `2379`.

### Explore ETCD
- K8s stores data in specific directory structre. Root directory is registery and under that we have various K8s constructs such as minions or nodes, pods, replicasets, deployments etc.
----
## Kube-API Server
- Primary Management component in K8s.
- When we run any `kubectl` command, it infact reaching to the Kube-API Server. Kube-Api server first authenticate and validate the request. It then retrives the data from ETCD cluster and responds back with the requested information.
- We can also invoke api directly by sending post request.

### Working Process
- When user make request to create new node, Kube-API server first authenticate and validates the request. Then it register the pod into ETCD cluster and give feedback to user that pod is created.
- Kube-Scheduler continuously monitors the API Server and realize that there is a new pod with no node assigned. The scheduler identifies right node to place the new pod on and communicates that back to the Kube-API Server.
- The API server update the information into ETCD Cluster and then passes these informations to Kubelet in appropriate worker node.
- The Kubelet then creates the Pod on the node and instructes the container runtime engine to deploy the application image.
- Once done, The kubelets update the status back to the API Server and API Server then updates the data into ETCD Cluster.
- A similar pattern follows everytime changes reflected.

#### Summary
- Authenticate User
- Validate Request
- Retrive Data
- Update ETCD
- Scheduler
- Kubelet
----
## Kube Controller Manager
- It manages various contollers in K8s.
- It continuously monitors te state of various components within the system and works towards bringing the whole system to the desired functioning state.

### Node Controller
- It is responsible for monitoring the status of the nodes and taking necessary actions to keep the application running.
- it does that through the Kube-API Server.
- it checks the status of the nodes every 5 seconds.
- If node fails it wait for 40 seconds to mark it as unreachable.
- After marking unreachable it waits for 5 mins for node to come back up, if does not then it removes the pod assigned to that node and provisioned them to the healthy one.

### Replication Controller
- It is responsible for monitoring the status of the Replica Sets and Ensuring that desired number of pods are available at all times within the set.
- if pod dies it creates another one.

#### Other K8s controller are as below...
- Deployment Controller
- Namespace Controller
- Job Controller
- EndPoint Controller
- Service Account Controller
- PV Binder Controller
- PV Protection Controller
- Stateful Set
- Replica Set
- Cron Job
- and much more...
- This all controllers are packaged into single process called **Kube-Controller Manager**. 
----
## Kube Scheduler
- It responsible for scheduling the pods on nodes.
- It only responsible for deciding which pod goes on which node. It does not actually place the pod on the node. That is the job of the kubelet
- Scheduler only decides which pod goes where.

### Why need scheduler?
- In K8s The Scheduler decides which nodes the pods are placed on depending on certain criteria. We may have Pods with different resource requirements, we can have nodes in the cluster dedicated to certain applications.
- The Scheduler looks at each Pods and tries to find best node for it.
- If one Pod require 10 CPU then there is possible that all the nodes in cluster does not have 10 or more than 10 CPUs, some of them have or some of them do not have.
----
## Kubelet
- Kubelet is like captain on the ship, It leads all the activity on Nodes.
- It registers the node with te Kubernetes Cluster. When It receives the instructions to load a container or POD on the node it requests the container runtime engine to pull the required image and run on the node.
- Kubelets then continues to monitor the state of the POD and the containers in it and reports to the Kube-API Server on a timely basis.
----
## Kube Proxy
- Within the K8s Cluster, every POD can reach every other pod, this is accomplished by deploying POD Netorking solution to the cluster.
- A Pod Network is an internal virtual network that spans across all the nodes in the cluster to which all the pods connect to.
- Kube-Proxy is a process that runs on the each node of the cluster. It's job is to look for new services and every time a new service is created it creates the appropriate rules on each nodes to forward traffic to those services to the backend Pods. One way it does this is using IPTABLES rules.
----
## PODs
- The containers are encapsulated into the K8s Object knows as Pods. A Pods is a single instance of an application and it's the smallest object in K8s.
- If we want to scale up we can create new Pods or New Nodes with Pods and to scale down we can delete Pods or Nodes as per the requiements.
- A single pod can ave multiple containers except for the fact that they are usually not multiple containers of the same kind.
- Multi Container are rare use case scenario and best practice suggest that we should run single container per Pod.
----
## Replication Controller and Replica Set
- What if for some reason our application crashes and users will no longer be able to access our application.
- To Prevent this we would like to run more than single instance at a time. So if one fails we still have other containers on which our app is running.
- The Replication Controller help us to run multiple Pods of single part thus providing High Availability. So even if we have single pod and if it crashes the replication controller can help by automatically bringing up the new pod.
- Replication Controller ensures that the specified number of pods are running at all times.
- It also help us to share load across the Pods.
- Replication Controller and Replica Set both are similar terms. Both have same Purpose but they are not the same.
- Replication Controller is the older technology that is being replaced by Replica Set.
- Replica Set monitors the Pods using Lable, Lable works as a filter for Replica Sets when there is 100s of Pods are running.
----
## Deployments
- Suppose we might want to deploy our app in production environment. We want to deploy multiple instances for web servers running.
- In addition to whenever newer version of app comes we also want to roll update on each instances one by one, and if one of the update results in unexpected error and we need to undo the recent change we would like to be able to roll back the changes that were recently carried out.
- Also we would like to do multiple changes in our production environment, such as modifying resources, scaling the environment etc... We do not want to apply the changes immediately after the command is run, instead we would like to pause the environment, make the changes and resumes the environment so all the changes roll-out together.
- All of these capabilities are available in K8s Deployments.
- The Deployments provides us with the capabilities to upgrade the underlying instaces, rolling updates, undo changes and Pause and Resume changes as required.
----
## NameSpaces
- K8s creates `Default` namespace automatically when the cluster is first setup. K8s also creates `Kube-System` namespace for it's internal purpose and the third namespace is called `kube-public` this is where resources that should be made available to all users are created.
- We can create our own NameSpaces as well.
- Each namespace can have it's own set of policies.We can also assign quota or resourcaes to each of these resources.
- - Resources within same namespace can refer each other using Names. If require resource can reach another namesapce as well.
----
## Services
- K8s services enables te communications between various components within and outside of the application.
- Services enables the loose coupling between microservices in our applications.
- K8s Service is the an object. There are multiple type of service available.
    - **NodePort Service**
       -    It's use case is to listen to a port on the Node and Forward requests on that Port to a Port on the POD running Web Application. Valid Port range for NodePort service is from 30000 to 32767.
    - **Cluster IP Service**
        - Service creates a Virtual IP inside the cluster to enable communication between diffrent services. Example set of frontend servers services to set of backend servers services.
    - **LoadBalancer Service**
        - It provisions a Load Balancer for our application in supported cloud providers. 