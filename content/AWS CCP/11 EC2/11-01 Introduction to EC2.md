---
title: 11-01 Introduction to EC2
date: 08/10/23
---

![35](images/icons/EC2_Icon.png) Elastic Cloud Compute (EC2) is a **highly configurable virtual server**. 

* EC2 is <span style="color:#ff0000">resizable compute capacity</span>.
* It takes **minutes** to launch new instances
* Everything on AWS uses EC2 underneath. 

## Steps to Configure EC2

### 1. Choose OS

Choose OS via **Amazon Machine Image (AMI)**

 > 
 > \[!example\]- Examples
 > 
 > * ![35](images/11_EC2/11-01/Red_Hat_Logo.png)
 > * ![35](images/11_EC2/11-01/Ubuntu_Logo.png)
 > * ![35](images/11_EC2/11-01/Windows_Logo.png)
 > * ![35](images/11_EC2/11-01/Amazon_Linux_Logo.png)
 > * ![35](images/11_EC2/11-01/SUSE_Logo.png)

### 2. Choose Instance Type

|**t2.nano**|**C4.8xlarge**|
|:-----:|:--------:|
|$0.0065/hour ($4.75/month)|$1.591/hour ($1161.43/month)|
|1 vCPU|36 vCPU|
|0.5GB Mem|60GB Mem|
|N/A|10 Gigabit performance|

### 3. Add Storage (EBS, EFS)

* SSD
* HDD
* Virtual Magnetic Tape
* Multiple Volumes

### 4. Configure Instance

* Security Groups
* Key Pairs
* UserData
* IAM Roles
* Placement Groups
