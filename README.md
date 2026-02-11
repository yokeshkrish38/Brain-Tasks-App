Project Title

Brain Tasks App Deployment using AWS DevOps

Architecture

GitHub → CodeBuild → ECR → EKS → LoadBalancer → Browser

Services Used

AWS ECR

AWS EKS

AWS CodeBuild

AWS IAM

AWS CloudWatch

GitHub

Deployment Steps

Dockerized React application

Pushed image to ECR

Created EKS cluster

Created Kubernetes deployment and service

Configured CodeBuild for CI/CD

Enabled CloudWatch logging

CI/CD Flow

On push to GitHub

CodeBuild triggers automatically

Docker image built

Image pushed to ECR

Kubernetes deployment updated

Application URL
http://a0ba501c60aa44d0aa709af5baba284f-810548627.us-east-1.elb.amazonaws.com/

LoadBalancer ARN
a0ba501c60aa44d0aa709af5baba284f
