---
title: 08-05 Storage Services
date: 07/10/23
---

## Simple Storage Service (S3)

\#aws-service   
![70](../../images/icons/S3_Icon.png)

* Simple Storage Service (S3) is a ==serverless object storage service.== 
* You can upload very large files and an unlimited amount fo files. 
* You can pay for what you store.
* You don't worry about the underlying file-system, or upgrading the disk size.

## S3 Glacier

![75](../../images/icons/S3_Glacier_Icon.png)

* S3 Glacier is a ==cold storage service==. 
* It is designed as a low cost storage solution for <mark style="background: #FF5582A6;">archiving and long-term backup</mark>. 
* It uses previous gen HDD drives to get that low cost.
* Highly secure and durable. 

## Elastic Block Store (EBS) - Block

\#aws-service   
![70](../../images/icons/Elastic_Block_Store_Icon.png)

* Data is split into evenly split blocks
* Directly accessed by the OS
* Supports only a single write volume
* in short, when you need a virtual hard drive attached to a VM

* Elastic Block Store (EBS) is a ==persistent block storage service==. 
* It is a virtual hard drive in the cloud you attach to EC2 instances. 
* You can choose different kinds of hard drives (SSD, IOPS SSD, Cold HDD)

## AWS Elastic File System (EFS) - File

\#aws-service   
![70](../../images/icons/Elastic_File_System_Icon.png)

* File is stored with data and metadata
* Multiple connections via a network share
* Supports multiple reads, writing locks the file
* in short, when you need a file-share where multiple users or VMs need to access the same drive

* Elastic File Storage (EFS) is a ==cloud-native NFS file system service==. 
* File storage you can mount to multiple EC2 instances at the same time
* When you need to share files between multiple servers

## Storage Service Terms

* **File Gateway** extends your local storage to AWS S3
* **Volume Gateway** caches your local drives to S3 so you have a continuous backup of local files in the cloud. 
* **Tape Gateway** stores files onto virtual tapes for backing up your files on very cost effective long term storage
