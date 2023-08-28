---
title: 26-09 High Availability and Elasticity on AWS
date: 08/24/23
---

## Examples

1. You are planning on developing a website in multiple languages such that you have one fleet of EC2 instances that serves the English version of your site and another fleet that serves the Spanish version of your site. For each language version, you will be configuring URLs with different paths such that the English version of your site will contain /en/ in the path and the Spanish version will contain /es/. ***Which type of load balancer would you use to route traffic to ensure users connect to the site in their desired language?***

* [ ] A. CLB
* [ ] B. NLB
* [ ] C. ALB
* [ ] D. Path-based load balancer

2. You are building a multi-tier architecture with web servers placed in the public subnet and application servers placed in the private subnet of your VPC. You need to deploy ELBs to distribute traffic to both the web server farm and the application server farm. Which type of load balancer would you choose to distribute traffic to your application servers?

* [ ] A. Internet-facing
* [ ] B. Internal load balancer
* [ ] C. Dynamic load balancer
* [ ] D. Static load balancer

3. Which ELB is ideal for handling volatile workloads and can scale to millions of requests per second?

* [ ] A. ALB
* [ ] B. NLB
* [ ] C. CLB
* [ ] D. Premium load balancer

4. Which configuration feature of the AWS Auto Scaling service enables you to define a maximum number of EC2 instances that can be launched in your fleet?

* [ ] A. Auto Scaling group
* [ ] B. Auto Scaling Launch Configuration
* [ ] C. Auto Scaling max fleet size
* [ ] D. Auto Scaling policy

5. When an ELB detects an unhealthy EC2 instance, which action does it perform regarding distributing incoming traffic?

* [ ] A. It continues to send traffic to the failed instance.
* [ ] B. It terminates the failed instance so that it is not part of the ELB target group.
* [ ] C. It only sends traffic to the remaining healthy instances.
* [ ] D. It restarts the unhealthy EC2 instance.

6. Which service does an AWS ALB integrate with to protect your applications from common web attacks?

* [ ] A. WAF
* [ ] B. Shield
* [ ] C. Inspector
* [ ] D. Key Management Service (KMS)

## Answers

 > 
 > \[!example\]- Answer
 > 
 > 1. C 
 > 1. B 
 > 1. B 
 > 1. A 
 > 1. C 
 > 1. A
