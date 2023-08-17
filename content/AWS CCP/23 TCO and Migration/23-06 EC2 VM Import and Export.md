---
title: 23-06 EC2 VM Import/Export
date: 08/16/23
---

VM Import/Export allows users **to import Virtual Machine images into EC2.**

AWS has import instructions for:

* VMWare
* Citrix
* Microsoft Hyper-V
* Windows VHD from Azure
* Linux VHD from Azure

````mermaid
flowchart TD
	A[1. Prepare Your Virtual Image for Upload] --> B[2. Upload your virtual image to S3]
	B --> C[3. Use the AWS CLI to export your image an AMI]
````
