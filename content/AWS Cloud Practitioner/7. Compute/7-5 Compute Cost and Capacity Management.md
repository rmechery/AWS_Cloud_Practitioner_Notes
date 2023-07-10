---
title: Compute Cost and Capacity Management
date: 07/09/23
---

**Capacity Management** - How do we meet the demand of traffic and usages by adding/upgrading servers?

## EC2 Spot Instances, Reserved Instanced and Savings Plan

Ways to save on computing, by paying up in full or partially, by committing to yearly contracts or by being flexible about availability and interruption to the computing service.

## AWS Batch

\#aws-service   
![35](../../images/icons/Batch_Logo.png) plans, schedules and executes ==your batch computing workloads== across the full range of AWS compute services, can utilize Spot Instance to save money. 

## AWS Compute Optimizer

\#aws-service   
![35](../../images/icons/Compute_Optimizer.png) suggests how to ==reduce costs and improve performance== by using machine leraning to analyze your previous usage history

## EC2 Autoscaling Groups (ASGs)

![35](../../images/icons/EC2_ASG_Icon.png) Automatically adds or remove EC2 servers to meet the current demand of traffic. Will save you money and met capacity since you only run the amount of servers you need.

## Elastic Load Balancer (ELB)

## Elastic Load Balancer

\#aws-service   
![images/icons/Elastic_Load_Balancing_Icon.png](../../images/icons/Elastic_Load_Balancing_Icon.png)

* A load balancer allows you to evenly distribute traffic to multiple servers in one or more datacenter. 
* If a datacenter or server becomes unavailable (unhealthy) the load balancer will route the traffic to only available datacenters with servers.

![450](../../images/3%20Global%20Infrastructure/4%20Cloud%20Architecture/High_Availability_Diagram.png)  
Running your workload across multiple Availability Zones ensures that if 1 or 2  
As become unavailable your service / applications remains available.

* Distributes traffic to multiple instance, can re-route traffic from unhealthy instance to healthy instances can route traffic to EC2 instances running in different Availability Zones

## AWS Elastic Beanstalk (EB)

\#aws-service   
![35](../../images/icons/Elastic_Beanstalk_Icon.png)  **AWS Elastic Beanstalk (EB)** is for easily deploying web-applications without developers having to worry about setting up and understanding the underlying AWS Services. 

 > 
 > \[!tip\] Note  
 > Similar to PaaS Service, Heroku.
