---
title: 06-04 Shared Responsibility Model - Architecture
date: 07/10/23
---

## Serverless/Functions - Less Responsibility

No more servers, just worry about data and code.  
Examples.

* **Amplify** Serverless Framework
* [Lambda](../7.%20Compute/07-02%20VMs,%20Containers%20and%20Serverless.md#aws-lambda) Serverless Architecture

## Microservices/Containers - More Responsibility

Mix and match languages, better utilization of resources  
Examples:

* [Fargate](../7.%20Compute/07-02%20VMs,%20Containers%20and%20Serverless.md#ecs-fargate) Serverless Containers
* [ECS](../7.%20Compute/07-02%20VMs,%20Containers%20and%20Serverless.md#elastic-container-service-ecs)/[EKS](../7.%20Compute/07-02%20VMs,%20Containers%20and%20Serverless.md#elastic-kubernetes-service-eks) Containers

## Traditional/VMs  - Most Responsibility

Global workforce is most familiar with this kind of architecture and lots of documentation, frameworks and support.  
Examples:

* [Elastic Beanstalk (EB)](../7.%20Compute/07-05%20Compute%20Cost%20and%20Capacity%20Management.md#aws-elastic-beanstalk-eb) Platform as a Service
* [EC2](../7.%20Compute/07-01%20EC2%20Overview.md) Infrastructure as a Service
