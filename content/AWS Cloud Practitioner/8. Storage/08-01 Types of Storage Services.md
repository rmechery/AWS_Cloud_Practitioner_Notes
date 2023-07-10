---
title: 08-01 Types of Storage Services
date: 07/10/23
---

## Elastic Block Store (EBS) - Block

\#aws-service   
![70](../../images/icons/Elastic_Block_Store_Icon.png)

* Data is split into evenly split blocks
* Directly accessed by the OS
* Supports only a single write volume
* in short, when you need a virtual hard drive attached to a VM

## AWS Elastic File System (EFS) - File

\#aws-service   
![70](../../images/icons/Elastic_File_System_Icon.png)

* File is stored with data and metadata
* Multiple connections via a network share
* Supports multiple reads, writing locks the file
* in short, when you need a file-share where multiple users or VMs need to access the same drive

## Amazon Simple Storage Service (S3) - Object

![70](../../images/icons/S3_Icon.png)

* Object is stored with data, metadata, and Unique ID
* Scales with no file limit or storage limit
* Supports multiple reads and writes (no locks)
