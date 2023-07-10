---
title: 3-8 Data Residency
date: 07/10/23
---

**What is data residency**  
The physical or geographic location of where an organization or cloud resources reside.

**What is Compliance Boundaries?**  
A regulatory compliance (legal requirement) by a government or organization that describes where data and cloud resources are allowed to reside

**What is Data Sovereignty?**  
Data Sovereignty is the jurisdictional control or legal authority that can be asserted over data because its physical location is within jurisdictional boundaries.

## Data Residency Cloud Services

For workloads that need to meet compliance boundaries strictly defining  
the data residency of data and cloud resources in AWS you can use:

### AWS Config

\#aws-service   
![images/icons/Config_Icon.png](../../images/icons/Config_Icon.png)  
**AWS Config** is a Policy as Code service. You can create rules to continuous check AWS resources configuration. If they deviate from your expectations you are alerted or AWS Config can in some cases auto-remediate.

### AWS Outposts

\#aws-service   
![images/icons/Outposts_Icon.png](../../images/icons/Outposts_Icon.png)  
**AWS Outposts** is physical rack of servers that you can put in your data center. Your data will reside whenever the Outpost Physically resides

### IAM Policies

\#aws-service   
![images/icons/IAM_Icon.png](../../images/icons/IAM_Icon.png)  
**IAM Policies** can be written to explicitly deny access to specific AWS Regions.

* A **Service Control Policy (SCP)** are permissions applied organization wide.
