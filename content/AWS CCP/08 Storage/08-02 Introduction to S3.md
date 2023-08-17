---
title: 08-02 Introduction to S3
date: 07/10/23
---

## What is Object Storage (Object -based Storage)?

data storage architecture that manages data as objects, *as opposed* to other storage architectures:

* **file systems** which manages data as files and fire hierarchy and
* **block storage** which manages data as blocks within sectors and tracks

## Advantages of S3

* S3 provides you with unlimited storage
* You don't need to think about the underlying infrastructure
* The S3 console provides an interface for you to upload and access your data

## S3 Object

\#aws-resource   
![75](images/icons/S3_Object_Icon.png)  
Objects contain your data. They are like files. Objects may consist of:

* **Key** this is the name of the object
* **Value** the data itself made up of a sequence of bytes
* **Version ID** when versioning enabled, the version of object
* **Metadata** additional information to the object
* You can store an individual object from 0 bytes to 5 terabytes in size

## S3 Bucket

\#aws-resource   
![75](images/icons/Bucket_Icon.png)

* Buckets hold objects
* Buckets can also have folders which in turn hold objects
* S3 is a universal namespace so bucket names must be unique (like domain names)
