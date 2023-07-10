---
title: 03-10 Ground Station
date: 07/10/23
---

![35](../../images/icons/Ground_Station_Icon.png) **AWS Ground Station** is a fully managed service that lets you control satellite communications, process data, and scale your operations without having to worry about building or managing your own ground station infrastructure. #aws-service 

 > 
 > \[!info\] Use Cases for Ground Station
 > 
 > * weather forecasting
 > * surface imaging
 > * communications
 > * video broadcasts

 > 
 > \[!tip\] Using the Ground Station
 > 
 > * You schedule a Contact (select satellite, start and end time, and the ground location)
 > * use the AWS Ground Station EC2 AMI to launch [EC2 instances](../7.%20Compute/07-01%20EC2%20Overview.md) that will uplink and downlink data during the contact or receive downlinked data in an Amazon [S3 Bucket](../8.%20Storage/08-02%20Introduction%20to%20S3.md#s3-bucket).

 > 
 > \[!example\]  
 > A company reaches an agreement with a Satellite Imagery Provider to  
 > take satellite photos of a specific region. They use AWS Ground Station to  
 > communicate that company's Satellite and download the [S3](../8.%20Storage/08-02%20Introduction%20to%20S3.md) image data.
