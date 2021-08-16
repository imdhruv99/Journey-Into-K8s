# ETCD
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