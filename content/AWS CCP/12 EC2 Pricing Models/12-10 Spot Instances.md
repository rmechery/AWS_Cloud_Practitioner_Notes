---
title: 12-10 Spot Instances
date: 08/11/23
---

AWS has unused compute capacity that they want to maximize the utility of their idle servers.

 > 
 > \[!example\] Example  
 > It’s like when a hotel offers booking discounts to fill vacant suites or planes offer discounts to fill vacant seats

[Amazon EC2 Spot Instances](https://aws.amazon.com/ec2/spot/) provide a discount of 90% compared to On-Demand Pricing

Spot Instances can be terminated if the computing capacity is needed by other On-Demand customers

Amazon EC2 Spot Instances let you take advantage of **unused EC2 capacity** in the AWS cloud.

Designed for applications that have flexible start and end times or applications that are only feasible at **very low** compute costs.

![35](images/icons/Batch_Logo.png)  [AWS Batch](https://aws.amazon.com/batch/) is an easy and convenient way to use Spot Pricing

**Termination Conditions:**

* Instances can be terminated by AWS **at any time.**
* If your instance is terminated by AWS, **you don't get charged** for a partial hour of usage.
* If you terminate an instance **you will still be charged** for an hour that it ran.
