---
title: 20-02 AWS CloudTrail
date: 08/15/23
---

## AWS CloudTrail

\#aws-service   
![35](images/icons/CloudTrail_Icon.png) **AWS CloudTrail** is a service that enables governance, compliance, operational auditing, and risk auditing of your AWS account.

AWS CloudTrail is used to monitor API calls and Actions made on an AWS account.

Easily identify which users and accounts made the call to AWS eg.

* **Where** — Source IP Address
* **When** — EventTime
* **Who** — User, UserAgent
* **What** — Region, Resource, Action

CloudTrail is already logging by default and will collect logs for the **last 90 days** via **Event History**

 > 
 > \[!warning\] Note  
 > If you need more than 90 days you need to create a **Trail**

Trails are output to S3 and do not have GUI like Event History. To analyze a Trail you’d have to use [Amazon Athena](../21%20ML,%20AI%20and%20Big%20Data/21-03%20Big%20Data%20and%20Analytics%20Services.md#2328c7).
