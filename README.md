# Text-Summarizer

## Workflow

1. Update config.yaml
2. Update params.yaml
3. Update entity
4. Update the configuration manager in src config
5. update the conponents
6. update the pipeline
7. update the main.py
8. update the app.py


##  Create IAM user for deployment
1. EC2 access : It is virtual machine

2. ECR: Elastic Container registry to save your docker image in aws

## policies
1. AmazonEC2ContainerRegistryFullAccess

2. AmazonEC2FullAccess

## Create ECR repo to store/save docker image
- Save the URI: 476203641051.dkr.ecr.us-east-1.amazonaws.com/text-s

## Configure EC2 as self-hosted runner:
setting>actions>runner>new self hosted runner> choose os> then run command one by one

## Setup github secrets:
AWS_ACCESS_KEY_ID=

AWS_SECRET_ACCESS_KEY=

AWS_REGION = us-east-1

AWS_ECR_LOGIN_URI = demo>>  566373416292.dkr.ecr.ap-south-1.amazonaws.com

ECR_REPOSITORY_NAME = simple-app

