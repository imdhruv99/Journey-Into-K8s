# Kube Scheduler
- It responsible for scheduling the pods on nodes.
- It only responsible for deciding which pod goes on which node. It does not actually place the pod on the node. That is the job of the kubelet
- Scheduler only decides which pod goes where.

### Why need scheduler?
- In K8s The Scheduler decides which nodes the pods are placed on depending on certain criteria. We may have Pods with different resource requirements, we can have nodes in the cluster dedicated to certain applications.
- The Scheduler looks at each Pods and tries to find best node for it.
- If one Pod require 10 CPU then there is possible that all the nodes in cluster does not have 10 or more than 10 CPUs, some of them have or some of them do not have.