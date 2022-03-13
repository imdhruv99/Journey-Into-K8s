# Scheduling
- In this section we take a closer look at the various options available for customizing and configuring the way scheduler behaves.

## Manual Scheduling
- We can schedule the pod manually by setting `nodeName` field to the name of the node in our pod specification file while creating the pod. The cache with this method is we can only assign this field at a creation time.
**pod-definition.yaml**
    ```
    apiVersion: v1
    kind: Pod
    metadata:
        name: nginx
        labels:
            name: nginx
    spec:
        containers:
        - name: nginx
          image: nginx
          ports: 
            - containerPort: 8080
        nodeName: node01
    ```
- A way to assign a `nodeName` to an existing pod is to create a binding object and send a post request to the pod binding API thus mimicking what the actual scheduler does. In binding object we need to specify a target node with the name of the node.
**pod-bind-definition.yaml**
    ```
    apiVersion: v1
    kind: Binding
    metadata:
        name: nginx
    target:
        apiVersion: v1
        kind: Node
        name: node01
    ```
    **post request**
    ```
    curl --header "Content-Type:application/json" --request POST data '{"apiVersion": "v1", "kind": "Binding", ...}''
    http://$SERVER/api/v1/namespaces/default/pods/$PODNAME/binding
    ```