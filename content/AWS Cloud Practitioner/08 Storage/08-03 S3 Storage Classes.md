---
title: 08-03 S3 Storage Classes
date: 07/10/23
---

AWS offers a range of S3 storage classes that *trade* **Retrieval, Time, Accessibility, and Durability** for <mark style="background: #FF5582A6;">Cheaper Storage</mark>

## S3 Standard (default)

* Fast! 
* 99.99% availability
* 11 9's Durability
* Replicated across at least three AZs

## S3 Intelligent Tiering

* Uses ML to analyze object usage and determine the appropriate storage class
* Data is moved to the most cost effective access tier, without any performance impact or added overhead

## S3 Standard-IA (infrequent access)

* Still Fast!
* Cheaper if you access files less than once a month
* Additional retrieval fee is applied.
* *50% less* than standard (reduced availability)

## S3 One-Zone-IA

* Still fast!
* Objects only exist in one AZ
* Availability is 99.5%
* cheaper than Standard IA (reduced durability bc data could get destroyed)
* A retrieval fee is applied

## S3 Glacier

* For long term cold storage
* Retrieval of data can take minutes to hours 
* very cheap storage 

## S3 Glacier Deep Archive

* The lowest cost storage class
* Data retrieval time is 12 hours
