# EKS Basics
----

### Create your AWS EKS Cluster using eksctl command line tool

- Run below command in terminal, you can modify all the parameters as per your needs.

    ```
    eksctl create cluster --name eksctl-test --nodegroup-name ng-default --node-type t3.micro --nodes 3
    ```

- Above command will take 15 to 20 mins for completion. Basically it will run `AWS CloudFormation` behind the scene.

- It will create cluster named as `eksctl-test` with 3 nodes.

- Now run below command to check status of EKS Cluster

    ```
    C:\Windows\system32>kubectl get all
    NAME                 TYPE        CLUSTER-IP   EXTERNAL-IP   PORT(S)   AGE
    service/kubernetes   ClusterIP   10.100.0.1   <none>        443/TCP   18m
    ```

- Now we create another node group, for that we will use config file named as `eks-create-ng.yaml`. Execute below command in terminal.

    ```
    eksctl create nodegroup --config-file=eks-create-ng.yaml
    ```

- This command will also run `AWS CloudFormation` behind the scene. It will also take 5 to 10 mins.
- After successfull execution of above command, verify the nodegroups using below command.

    ```
    D:\GitHub\Kubernetes-AWS-EKS>eksctl get nodegroup --cluster=eksctl-test
    2021-06-21 18:48:08 [ℹ]  eksctl version 0.54.0
    2021-06-21 18:48:08 [ℹ]  using region us-east-1
    CLUSTER         NODEGROUP       STATUS          CREATED                 MIN SIZE        MAX SIZE        DESIRED CAPACITY        INSTANCE TYPE   IMAGE ID                ASG NAME
    eksctl-test     mng-demo        ACTIVE          2021-06-21T13:14:18Z    1               3               2                       t3.micro        AL2_x86_64              eks-aabd175a-8893-6b10-4912-3d9e2a6f725a
    eksctl-test     ng-default      CREATE_COMPLETE 2021-06-21T12:58:19Z    2               2               2                       t3.micro        ami-0ef0c69399dbb5f3f   eksctl-eksctl-test-nodegroup-ng-default-NodeGroup-XT8ER2WA77QQ
    eksctl-test     ng-demo         CREATE_COMPLETE 2021-06-21T13:13:33Z    2               2               2                       t3.micro        ami-0ef0c69399dbb5f3f   eksctl-eksctl-test-nodegroup-ng-demo-NodeGroup-83S5W7PXTYUF
    ```

- We can also create all these using command and giving bunch of parameters in command.

- Now we create cluster using config file `eks-create-cluster.yaml`. Execute below command in terminal.

    ```
    eksctl create nodegroup --config-file=eks-create-cluster.yaml
    ```

- This command will also run `AWS CloudFormation` behind the scene and It will also take 5 to 10 mins.


- Below are the screenshot of AWS Console of EC2, CloudFormation and EKS.

![AWS EC2 Console](https://github.com/imdhruv99/Kubernetes-AWS-EKS/blob/main/Images/ec2_eks_test_.png)

![AWS CloudFormation Console](https://github.com/imdhruv99/Kubernetes-AWS-EKS/blob/main/Images/cf_eks_test.png)

![AWS EKS Console](https://github.com/imdhruv99/Kubernetes-AWS-EKS/blob/main/Images/eks_eks_test.png)

- We can delete the cluster using below command.

    This command will list all the cluster
    ```
    D:\GitHub\Kubernetes-AWS-EKS>eksctl get cluster
    2021-06-21 19:19:55 [ℹ]  eksctl version 0.54.0
    2021-06-21 19:19:55 [ℹ]  using region us-east-1
    NAME            REGION          EKSCTL CREATED
    eksctl-test     us-east-1       True
    ```

    Now delete the cluster, beind the scene it will delete the `AWS CloudFormation`
    ```
    eksctl delete cluster --name=eksctl-test 
    ```

    We can confirm that cluster is deleted using 
    ```
    D:\GitHub\Kubernetes-AWS-EKS>eksctl get cluster
    2021-06-21 19:25:59 [ℹ]  eksctl version 0.54.0
    2021-06-21 19:25:59 [ℹ]  using region us-east-1
    No clusters found
    ``` 