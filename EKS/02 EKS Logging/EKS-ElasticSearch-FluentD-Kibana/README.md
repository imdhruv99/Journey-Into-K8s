# EKS-ElasticSearch-FluentD-Kibana
----

### Create Cluster

- Create cluster named as `eks-efk` using below command

    ```
    eksctl create cluster -f cluster.yaml
    ```

### Attach Logging policies in IAM Role of EC2

- Go to EC2 Console, Select EC2, Select single Instance
- Go IAM Role under Description
- Open Policies
- Click on Attach Policy and Attach `CloudWatchLogsFullAccess`.

### Setup FluentD

- We will deploy fluentD using `fluentd.yml` file.

- This manifest file will create ServiceAccount, ClusterRole, ClusterRoleBinding, ConfigMap and DaemonSet.

- Deploy this file using below command...

    ```
    kubectl apply -f fluentd.yml
    ```

- This will install fluentD in the namespace `kube-system`.

- After this, go to AWS CloudWatch Console, Go to Log Groups from left navigation bar and you should see log group for this cluster created buy fluentD.

### Deploying Service

- Now, we will deploy LoadBalancer Service on created cluster.
- We will deploy `nginx` using `loadbalancer-service.yaml`.

- Deploy `loadbalancer-service.yaml` using below command...

    ```
    kubectl apply -f loadbalancer-service.yaml
    ```

- Verified deployment using below command

    ```
    D:\GitHub\Kubernetes-AWS-EKS\03 EKS Logging\EKS-ElasticSearch-FluentD-Kibana>kubectl get all
    NAME                                       READY   STATUS    RESTARTS   AGE
    pod/frontend-deployment-6555f86498-dfdm9   0/1     Pending   0          37s
    pod/frontend-deployment-6555f86498-pgwp4   1/1     Running   0          37s

    NAME                 TYPE           CLUSTER-IP     EXTERNAL-IP                                                               PORT(S)        AGE
    service/kubernetes   ClusterIP      10.100.0.1     <none>                                                                    443/TCP        27m
    service/lb-service   LoadBalancer   10.100.2.101   a70a61566fc6d43c3af489d3309de457-1429811813.us-east-1.elb.amazonaws.com   80:30701/TCP   40s

    NAME                                  READY   UP-TO-DATE   AVAILABLE   AGE
    deployment.apps/frontend-deployment   1/2     2            1           41s

    NAME                                             DESIRED   CURRENT   READY   AGE
    replicaset.apps/frontend-deployment-6555f86498   2         2         1       42s
    ```

- It takes 5 mins to logs to propogate to cloudwatch.

- Now node groups will be created but we did not invok the pods. So let's invoke pods

- First invoke `nginx` pods using LB available in `EXTERNAL-IP` and then invoke `hello-k8s`.

- Now go to `Log Groups` under the AWS CloudWatch and open `frontend-deployment-******` service, you should see some logs such as below


### Create ElasticSearch using AWS CLI

- Use below command to create ES

    ```
    aws es create-elasticsearch-domain --domain-name eks-logs --elasticsearch-version 7.10 --elasticsearch-cluster-config InstanceType=t2.small.elasticsearch,InstanceCount=1 --ebs-options EBSEnabled=true,VolumeType=standard,VolumeSize=10
    ```

- It will create ElasticSearch named as `eks-logs`. Go to AWS ElasticSearch Console, It will take time to spin-up the cluster.

- Now go to AWS IAM, create role named as `lambda_role` with common use case as `Lambda` and with permission of `AmazonESFullAccess`.

- Now go to AWS CLoudWatch, Click on Actions, Click on `Create Elasticsearch subscription filter`.

- Select the `eks-logs` from Amazon ES cluster and select `lambda_es` from Lambda IAM Execution Role under `Choose destination`.\

- Select Log Format as `Common Log Format` and click on `Start Streaming`.