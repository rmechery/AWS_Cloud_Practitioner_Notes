---
title: 17-02 AWS Elastic Beanstalk
date: 08/15/23
---

## **What is Platform as a Service? (PaaS)**

a [PaaS](../01%20Cloud%20Concepts/01-07%20Types%20of%20Cloud%20Computing.md#platform-as-a-service-paas) allows customers to develop, run, and manage applications without the complexity of building and maintaining the infrastructure typically associated with developing and launching an app

## Elastic Beanstalk

![35](images/icons/Elastic_Beanstalk_Icon.png) **Elastic Beanstalk** is a PaaS for deploying web applications with little-to-no knowledge of the underlying infrastructure so you can focus on writing application code instead of setting up an automated deployment pipeline and DevOps tasks.

Choose a platform, upload your code and it runs with little knowledge of the infrastructure.

 > 
 > \[!warning\] Note  
 > Not Recommended for <span style="color:#f8857d">Production</span> applications  
 > *However*, AWS is talking about enterprises, large companies.

Elastic Beanstalk is powered by a [CloudFormation](17-01%20Provisioning%20Services.md#ff9a8c) template and **setups** for you:

* [Elastic Load Balancer](../04%20Cloud%20Architecture/04-02%20High%20Availability.md#elastic-load-balancer)
* [Autoscaling Groups](../07%20Compute/07-05%20Compute%20Cost%20and%20Capacity%20Management.md#ec2-autoscaling-groups-asgs)
* [RDS](../10%20Databases/10-05%20Relational%20Database%20Services.md#839368) Database
* EC2 Instance preconfigured (or custom ) platforms
* Monitoring ([CloudWatch](../20%20Logging/20-01%20Logging%20Services.md#cloudwatch), [SNS](../14%20Application%20Integration/14-04%20Pub%20Sub.md#simple-notification-service-sns))
* In-Place and Blue/Green deployment methodologies
* Security (Rotates passwords)
* Can run [Dockerized](../15%20Containers/15-04%20Docker.md) environments
