# Kube-API Server
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