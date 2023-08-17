---
title: 18-02 Serverless Services
date: 08/15/23
---

## What is Serverless?

When the underlying servers, infrastructure, and Operating System (OS) is taken care of by the [Cloud Service Provider (CSP)](../01%20Cloud%20Concepts/01-02%20Cloud%20Service%20Provider%20CSP.md).​

Serverless is generally by default highly available, scalable and cost-effective. You pay for what you use.​

[DynamoDB](../10%20Databases/10-04%20NoSQL%20Database%20Service.md#dynamodb) - is a serverless NoSQL key/value and document database. It is designed to scale to billions of records with guaranteed consistent data return in at least a second. You don’t have to worry about managing shards!​

[Simple Storage (S3)](../08%20Storage/08-05%20Storage%20Services.md#simple-storage-service-s3) - is a serverless object storage service. You can upload very large and an unlimited amount of files. You pay for what you store. You don’t worry about the underlying file-system, or upgrading the disk size.​

[ECS Fargate](../07%20Compute/07-02%20VMs,%20Containers%20and%20Serverless.md#ecs-fargate) - is serverless orchestration container service. It is the same as ECS except you pay-on-demand per running container (With ECS you have to keep an EC2 server running even if you have no containers running) AWS manages the underlying server, so you don’t have to scale or upgrade the EC2 server.​

[AWS Lambda](../07%20Compute/07-02%20VMs,%20Containers%20and%20Serverless.md#aws-lambda) - is a serverless functions service. You can run code without provisioning or managing servers. You upload small pieces of code, choose how much memory, and how long the function is allowed to run before timing out. You a charged based on the runtime of the serverless function rounded to the nearest 100ms.​

[Step Functions](../14%20Application%20Integration/14-06%20State%20Machines.md#aws-step-functions) - is a state machine service. It coordinates multiple AWS services into serverless workflows. Easily share data among Lambdas. Have a group of lambdas wait for each other. Create logical steps. Also works with Fargate Tasks.​

[Aurora Serverless](../10%20Databases/10-05%20Relational%20Database%20Services.md#a75407) - is the serverless on-demand version of Aurora. When you want "most" of the benefits of Aurora but can trade to have cold-starts or you don't have lots of traffic demand
