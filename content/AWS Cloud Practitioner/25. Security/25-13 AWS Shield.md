---
title: 25-13 AWS Shield
date: 08/16/23
---

## AWS Shield

\#aws-service   
![35](images/icons/Shield_Icon.png) **AWS Shield** is a **managed** DDoS (Distributed Denial of Service) protection service that safeguards applications running on AWS

* When you route your traffic through **Route 53** or **CloudFront** you are using **AWS Shield Standard**
* Protects you against **Layer 3 and 4** attacks
  * 4 Transport
  * 3 Network

### Shield Standard FREE

<span style="color:#ef857d">protection against most common DDoS attacks</span>

* access to tools and best practices to build a DDoS resilient architecture.
* Automatically available on all AWS services.

### **Shield Advanced** $3000 / Year

<span style="color:#ef857d">additional protection against larger and more sophisticated attacks</span>
  
Available On

* Amazon Route 53
* Amazon CloudFront
* Elastic Load Balancing
* AWS Global Accelerator
* Elastic IP (Amazon EC1 and Network Load Balancer)

Notable Features

* Visibility and Reporting on Layer 3,4 and 7
  * 7 Application
  * 4 Transport
  * 3 Network
* Access to Team and Support (with Business or Enterprise Support)
* DDoS Cost Protection
* Comes with SLA

 > 
 > \[!tip\] Note  
 > Both plans integrate with AWS Web Application Firewall (WAF) to give you Layer 7 (Application) protection
