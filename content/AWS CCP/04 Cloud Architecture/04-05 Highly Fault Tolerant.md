---
title: 04-05 Highly Fault Tolerant
date: 07/10/23
---

Your ability for your service to ensure there is ==no single point of failure.== Preventing the chance of failure.

**Fail-overs** are when you have a plan to *shift traffic* to a redundant system in case the primary system fails.

 > 
 > \[!example\] Example  
 > ![300](images/04_Cloud_Architecture/Fault_Tolerance_Diagram.png)  
 > A common example is having a copy (secondary) of your database where all ongoing changes are synced. The secondary system is not in-use until a fail over occurs and it becomes the primary database.

## RDS Multi-AZ

\#aws-service  #aws-resource   
![55](images/icons/RDS_Icon.png) ![65](images/icons/RDS_Multi_AZ_Icon.png)   
**RDS Multi-AZ** is an AWS Service that lets you run a duplicate standby database in another Availability Zone in case your primary database fails.
