# Cats in container ( Code Pipeline Project)

This project has been forked from
[Adrian Cantrill's](https://github.com/acantril) [catpipeline repo](https://github.com/acantril/learn-cantrill-io-labs/tree/master/aws-codepipeline-catpipeline).I have added my own sub project in the pipeline.The project contains various stages.

# Screenshots

## 1

![fullscreenshot](https://github.com/cbetz/flutter-vision/assets/34231063/c5cb1f05-2365-4bd7-92c3-1b2af700a474)

## 2

![screenshot3](https://github.com/cbetz/flutter-vision/assets/34231063/4f52c89a-a6c3-4580-800f-d56f04d44df3)

## 3

![mobileView](https://github.com/cbetz/flutter-vision/assets/34231063/b9ae5102-7593-403c-a11a-d71bf05c44d6)

# Steps

- STAGE 1 : Configure Security & Create a CodeCommit Repo

- STAGE 2 : Configure CodeBuild to clone the repo, create a container image and store on ECR

- STAGE 3 : Configure a CodePipeline with commit and build steps to automate build on commit.

- STAGE 4 : Create an ECS Cluster, TG's , ALB and configure the code pipeline for deployment to ECS Fargate

- STAGE 5 : CLEANUP
