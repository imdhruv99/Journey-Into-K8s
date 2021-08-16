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

