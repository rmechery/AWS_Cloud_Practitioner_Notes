---
title: VMs, Containers and Serverless
date: 07/09/23
---

## Virtual Machines

### Amazon LightSail

\#aws-service   
![35](../../images/icons/Lightsail_Icon.png)  Amazon LightSail is the ==managed virtual server service.== It is the "friendly" version of EC2 Virtual Machines   
*When you need to launch a Linux or Windows server but don't have much AWS knowledge. eg. Launch a Wordpress*

## Containers

\#aws-category  
![35](../../images/icons/Containers_Icon.png) Virtualizing an OS to run multiple workloads on a single OS instance.   
Containers are generally used in microservice architecture (when you divide your application into smaller applications that talk to each other) 

### Elastic Container Service (ECS)

\#aws-service   
![35](../../images/icons/ECS_Icon.png)  Elastic Container Service (ECS) is a ==container orchestration service== that supports Docker containers. Launches a cluster of server(s) on EC2 instances with Docker installed. <span style="color:#b3b3b3">when you need docker as a service, or you need to run containers.</span>

### Elastic Container Registry (ECR)

\#aws-service   
![35](../../images/icons/ECR_Icon.png) Elastic Container Registry (ECR) is a ==repository for container images==. In order to launch a container you need an image. An image just means a saved copy. A repository just means storage that has version control. 

### ECS Fargate

\#aws-service   
![35](../../images/icons/Fargate_Icon.png) ECS Fargate is a ==serverless orchestration container service==. It is the same as ECS except you pay-on-demand per running container (With ECS you have to keep a EC2 server running even if you have no containers running) AWS manages the underlying server, so you don't have to scale or upgrade the EC2 server. 

### Elastic Kubernetes Service (EKS)

\#aws-service   
![35](../../images/icons/EKS_Icon.png)  Elastic Kubernetes Service (EKS) is a ==fully managed Kubernetes service==. Kubernetes (K8) is an open-source orchestration software that was created by google and is generally the standard for managing microservices. <em style="color:#b3b3b3">when you need to run Kubernetes as a service</em>

## Serverless

\#aws-category   
![35](../../images/icons/Serverless_Icon.png) when the underlying servers are managed by AWS. You don't worry or configure servers.

### AWS Lambda

\#aws-service   
![35](../../images/icons/Lambda_Icon.png) AWS Lambda is a ==serverless functions service.== You can run code without provisioning or managing servers. You upload small pieces of code, choose much memory and how long the function is allowed to run before timing out. You are charged based on the runtime of the serverless function rounded to the nearest 100ms.
