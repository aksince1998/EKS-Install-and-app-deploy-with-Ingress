# Install EKS

Please follow the prerequisites doc before this.

## Install using Fargate

```
eksctl create cluster --name demo-cluster --region us-east-1 --fargate
```

#After completion of task please delete the cluster along with resources

## Delete the cluster

```
eksctl delete cluster --name demo-cluster --region us-east-1
```


