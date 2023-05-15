# Cats in container ( Code Pipeline Project)

This project has been forked from
[Adrian Cantrill's](https://github.com/acantril) [catpipeline repo](https://github.com/acantril/learn-cantrill-io-labs/tree/master/aws-codepipeline-catpipeline).The project contains various stages:-

- STAGE 1 : Configure Security & Create a CodeCommit Repo

- STAGE 2 : Configure CodeBuild to clone the repo, create a container image and store on ECR

- STAGE 3 : Configure a CodePipeline with commit and build steps to automate build on commit.

- STAGE 4 : Create an ECS Cluster, TG's , ALB and configure the code pipeline for deployment to ECS Fargate

- STAGE 5 : CLEANUP
