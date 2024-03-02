# 2048 App

## Create Fargate profile

```
eksctl create fargateprofile ^
    --cluster demo-cluster ^
    --region us-east-1 ^
    --name alb-sample-app ^
    --namespace game-2048
```

## Deploy the deployment, service and Ingress

```
kubectl apply -f https://raw.githubusercontent.com/kubernetes-sigs/aws-load-balancer-controller/v2.5.4/docs/examples/2048/2048_full.yaml
```

![game-2048](https://github.com/aksince1998/EKS-Install-and-app-deploy-with-Ingress/assets/148586317/48c3f6c7-1c83-4003-8425-a45b29296249)



