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

## Labels & Selectors
- Labels & Selectors are standard method to group things together.

    **How Lables & Selectors work in K8s?**
    - We create a lot of different types of objects in K8s, such as Pods, Services, ReplicaSets and Deployments. For K8s these are  different objects. Over the time we may end up having hundreds or thousands of these objects in cluster. 
    - So, We need a way to filter and view different objects by different categories, such as group objects by type or application.
    - We can do these filters using Labels and Selectors.
    
    **Annotations**
    - Annotations are used to record details for informatory purpose.
    
    **Labels in pod-definition.yaml**
    ```
    apiVersion: v1
    kind: Pod
    metadata:
        name: my-web-app
        labels:
            app: web-app
            function: front-end
    ```
    
    **Selector using Kubectl**
    ```
    kubectl get pods --selector app=web-app
    ```
    
    **replicaset-definition.yaml**
    ```
    apiVersion: v1
    kind: ReplicaSet
    metadata:
        name: my-web-app
        labels:
            app: web-app
            function: front-end
        annotations:
            buildversion: 1.1
            email: hello@gmail.com
    
    spec:
        replicas: 3
        selector:
            matchLabels:
                app: web-app
        template:
            metadata:
                labels:
                    app: web-app
                    function: front-end
            spec:
                containers:
                - name: web-app
                  image: web-app  
    ```
    - Here, Labels define under the template section are the labels configure for Pods and Labels define on top are the labels for ReplicaSet.
    - Selector field is used to connect ReplicaSet to Pods.

## Taints and Tolerations
- Taints and Tolerations have nothing to do with security or intrusion on the cluster. Taints and Tolerations are used to set restrictions on what pods can be scheduled on a node.
- They does not tell pods to go on particular node. Instead it tells node to only accept pods with certain toleration.
    
    #### Taint
    They allow a node to repel a set of pods
    There are three taint effects
    **NoSchedule:** Pods will not be scheduled on the Nods
    **NoExecute:** New Pods will not be scheduled on the node and existing pods on the node will be evicted if they do not tolerate the taint. 
    **PreferNoSchedule:** The System will try to avoid placing a pod on the node but that is not surity.
    ```
    kubectl taint nodes node-name key=value:<taint-effect>
    
    kubectl taint nodes node1 app=blue:NoSchedule
    ```
    
    #### Tolerations
    Tolerations are applied to pods, and allow (but do not require) the pods to schedule onto nodes with matching taints.
    
    **pod-definition.yaml**
    ```
    apiVersion: v1
    kind: Pod
    metadata:
        name: my-web-app
    spec:
        containers:
        - name: nginx-container
          image: nginx
        tolerations:
        - key: "app"
          operator: "Equal"
          value: "blue"
          effect: "NoSchedule"
    ```