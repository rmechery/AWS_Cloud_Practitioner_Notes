---
title: 26-06 VPCs, Route53, and CloudFront
date: 08/24/23
---

## Questions

1. Which VPC component enables to you grant internet access to servers in the public subnet deployed in the VPC?

* [ ] A. NAT gateway
* [ ] B. Internet gateway 
* [ ] C. VPC peering
* [ ] D. Security group

2. Which of the following statements are true?

* [ ] A. NACLs protect entire subnets, whereas security groups protect the individual instance.
* [ ] B. NACLs protect the individual instance, whereas security groups protect the entire subnet.
* [ ] C. NACLs enable instances in the private subnet to access the internet and act as a NAT device, whereas security groups are used to assign IAM policies to servers that need access to S3 buckets.
* [ ] D. NACLs enable instances in the private subnet to access the internet and act as a NAT device, whereas security groups are used to assign IAM policies to servers that need access to S3 buckets.

3. Which AWS service enables you to purchase and register new domain names that can be used to publish your website on the internet?

* [ ] A. Route53
* [ ] B. VPC
* [ ] C. RDS
* [ ] D. Elastic Beanstalk

4. Which AWS service enables you to distribute your digital assets such that it is cached locally to users who attempt to access this content for a time to live, and thus helps to reduce network latency?

* [ ] A. AWS CloudFront 
* [ ] B. AWS CloudTrail 
* [ ] C. AWS CloudWatch 
* [ ] D. AWS CloudScape

5. Your organization hosts multiple AWS accounts with multiple VPCs. You would like to connect these VPCs together and centrally manage connectivity policies. Which AWS service enables you to connect multiple VPCs configured as a hub that controls how traffic is routed among all the connected networks, which act like spokes?

* [ ] A. AWS Transit Gateway
* [ ] B. AWS Global Accelerator
* [ ] C. AWS VPC Peering
* [ ] D. AWS Virtual Private Gateway

6. Which AWS service enables you to grant internet access to EC2 instances configured with IPv4, and located in the private subnet of your VPC?

* [ ] A. Egress-only internet gateway 
* [ ] B. NAT gateway
* [ ] C. VPC endpoint
* [ ] D. VPN tunnel

7. You company has a primary production website in the US and a DR site in Sydney. You need to configure DNS such that if your primary site becomes unavailable, you can fail DNS over to the secondary site. Which DNS routing policy can you configure to achieve this?

* [ ] A. Weighted Routing
* [ ] B. Geolocation Routing 
* [ ] C. Latency Routing
* [ ] D. Failover Routing

8. You plan to set up DNS failover using Amazon Route53. Which feature of Route53 can you use to test your web application's availability and reachability?

* [ ] A. Private DNS 
* [ ] B. CloudWatch 
* [ ] C. Health checks 
* [ ] D. DNS ping

9. Which VPC firewall solution enables you to deny inbound traffic from a specific IP address, which can be used to prevent malicious attacks?

* [ ] A. AWS Firewall
* [ ] B. AWS Security Groups
* [ ] C. AWS Network Access Control Lists (NACLs) 
* [ ] D. AWS CloudFront

10. Which AWS service enables you to connect your private data center to your Amazon VPC with up to 100 Gbps network connectivity?

* [ ] A. Snowball
* [ ] B. Direct Connect
* [ ] C. Virtual Private Network (VPN) 
* [ ] D. Virtual Satellite Network (VSN)

## Answers

 > 
 > \[!example\]- Answers
 > 
 > 1. B 
 > 1. A 
 > 1. A 
 > 1. A 
 > 1. A 
 > 1. B 
 > 1. D 
 > 1. C 
 > 1. C 
 > 1. B
