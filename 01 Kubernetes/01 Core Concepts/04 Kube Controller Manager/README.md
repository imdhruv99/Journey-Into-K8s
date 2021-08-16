# Kube Controller Manager
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