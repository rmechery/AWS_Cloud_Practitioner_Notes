---
title: 20-01 Logging Services
date: 08/15/23
---

Amazon Web Services (AWS) provides service-specific operational metrics and log files to give customers insight into how the service is operating.

## CloudTrail

![75](images/icons/CloudTrail_Icon.png)  
Cloud Trail - logs all API calls (SDK, CLI) between various AWS services

 > 
 > \[!example\] Example Questions that CloudTrail can answer:  
 > *Who created this bucket?* - detect developer mis-configuration  
 > *Who spun up that expensive EC2 instance?* - Detect malicious actors  
 > *Who launched this SageMaker notebook?* - Automate responses

## CloudWatch

\#aws-service   
![75](images/icons/CloudWatch_Icon.png)  
CloudWatch - is a collection of multiple services

* CloudWatch **Logs** : Performance data about AWS Services eg. CPU Utilization, Memory, Network in Application Logs eg. Rails, Nginx Lambda Logs
* CloudWatch **Metrics**: Represents a time-ordered set of data points. A variable to monitor
* CloudWatch **Events**: trigger an event based on a condition eg. every hour take a snapshot of the server
* CloudWatch **Alarms**: triggers notifications based on metrics
* CloudWatch **Dashboard**: create visualizations based on metrics

## X-Ray

\#aws-service   
![75](images/icons/X-Ray_Icon.png)  
AWS X-Ray is a distributed tracing system. You can use it to pinpoint issues with your microservices.​ See how data moves from one app to another, how long it took to move, and if it failed to move forward.
