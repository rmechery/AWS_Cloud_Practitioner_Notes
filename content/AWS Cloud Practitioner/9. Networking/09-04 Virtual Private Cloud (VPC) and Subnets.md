---
title: 09-04 Virtual Private Cloud (VPC) and Subnets
date: 07/10/23
---

![450](../../images/9%20Networking/Virtual_Private_Cloud_and_Subnets.drawio.svg)

**Virtual Private Cloud (VPC)** is a logically isolated section of the AWS Network where you launch your AWS resources. You choose a <mark style="background: #FF5582A6;">range of IPS using CIDR Range</mark>

CIDR Range of ==10.0.0.0/16 = 65,5356== IP Addresses

**Subnets** are a logical partition of an IP network into multiple smaller network segments. ==You are breaking up your IP range for VPC== into smaller networks.

Subnets <mark style="background: #FF5582A6;">need to have a smaller CIDR range than the VPC</mark> to repreesent their portion  
ex. Subnet CIDR Range 10.0.0.0/24 = 256 IP Addresses

A **Public Subnet** is one that *can* reach the internet

A **Private Subnet** is one that *cannot* reach the internet
