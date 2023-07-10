---
title: 07-01 EC2 Overview
date: 07/10/23
---

![35](../../images/icons/EC2_Icon.png) **Elastic Compute Cloud (EC2)** allows you to launch <span style="color:#ff0000">Virtual Machines (VM)</span>
  
\#aws-service 

## What is a Virtual Machine?

A Virtual Machine (VM) is an emulation of a physical computer using software.  
Server Virtualization allows you to easily ==create, copy, resize or migrate== your server.  
Multiple VMs can run <span style="color:#ff0000">on the same physical server</span> so you can share the cost with other customers.  
*Imagine if your server or computer was an executable file on your computer*

When we launch a virtual machine we call it an "instance"

# Amazon Machine Image (AMI)

\#aws-resource   
![35](../../images/icons/AMI_Icon.png) EC2 is ==highly configurable== where you can choose an **amazon machine image (AMI)** that affects options such as:

* the amount of CPUs
* the amount of memory
* the amount of network bandwith
* the operation system (OS) eg. Windows 10, Ubuntu, Amazon Linux 2
* Attach multiple virtual hard-drives for storage eg. Elastic Block Store (EBS)

## Why is EC2 the backbone of AWS?

EC2 is also considered <span style="color:#ff0000">the backbone of AWS</span> because the majority of AWS services use EC2 as the underlying server  
eg. S2, RDS, DynamoDB, Lambdas
