## Virtual Machine Sheet Link

https://docs.google.com/spreadsheets/d/1Sz-0vXdj42LUURmis3OsUwsbiVcrCIiicJkSe4tUmQ4/edit?usp=sharing

## AWS User

https://dc-lab.signin.aws.amazon.com/console

## EKS Cluster Connecting Commands

aws eks --region us-east-1 describe-cluster --name hiteshnewCluster --query cluster.status

aws eks --region us-east-1 update-kubeconfig --name hiteshnewCluster
