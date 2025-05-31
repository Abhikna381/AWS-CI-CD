## End to End MAchine Learning Project

1. Docker Build checked
2. Github Workflow
3. Iam User In AWS

## Docker Setup In EC2 commands to be Executed

## OPTIONAL:

sudo apt-get update -y

sudo apt-get upgrade

## REQUIRED:

curl -fsSL https://get.docker.com -o get-docker.sh

#sudo dnf install docker -y
#sudo systemctl start docker
#sudo systemctl enable docker

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu #ubuntu is username in ubuntu based ec2 instance
sudo usermod -aG docker ec2-user

newgrp docker

## Configure EC2 as self-hosted runner:

## Setup github secrets:

AWS_ACCESS_KEY_ID=

AWS_SECRET_ACCESS_KEY=

AWS_REGION = us-east-1

AWS_ECR_LOGIN_URI = demo>>  566373416292.dkr.ecr.ap-south-1.amazonaws.com

ECR_REPOSITORY_NAME = simple-app
# AWS-CI-CD DEPLOYMENT
