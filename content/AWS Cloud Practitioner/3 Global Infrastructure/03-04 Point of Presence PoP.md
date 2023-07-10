---
title: 03-04 Point of Presence PoP
date: 07/10/23
---

==Points of Presence (PoP)== is an intermediate location between an [AWS Region](03-01%20Global%20Infrastructure.md#regional-services) and the end user, and this location could be a [datacenter](03-01%20Global%20Infrastructure.md#b2786e) <span style="color:#ff0000">owned by AWS or a trusted partner</span> that is utilized by AWS Services related for **content delivery or expedited upload**. 

Live at the edge/intersection of two networks.   
![450](../../images/3%20Global%20Infrastructure/PoP_Diagram.png)  
A ==Tier 1 Network==  is a network that can reach every other network on the Internet <span style="color:#ff0000"></span><span style="color:#ff0000">without purchasing IP transit or paying for peering</span>. 

## Edge Locations

==Edge Locations== are datacenters that hold cache (copy) on the most popular files (e.g. web pages & images) so that the delivery of distance to the end users are reduced. 

## Regional Edge Locations

==Regional Edge Locations== are datacenters that hold much larger caches of less-popular files to reduce a full round trip and also to reduce the cost of transfer fees. 

## AWS Services using PoP

The following AWS services use PoPs for content delivery or expedited upload:

### Amazon CloudFront

\#aws-service   
![images/icons/CloudFront_Icon.png](../../images/icons/CloudFront_Icon.png)  
==**Amazon CloudFront**== is a Content Delivery Network (CDN) that:   ^d7096a  
\* You point your website to CloudFront so that it will route requests to nearest Edge Location cache   
\* allows you to choose an <span style="color:#ff0000">origin</span> (such as a web-server or storage) that will be source of cached  
\* caches the contents of what origin would returned to various Edge Locations around the world

### Amazon S3 Transfer Acceleration

\#aws-service   
![images/icons/S3_Icon.png](../../images/icons/S3_Icon.png)  
**==Amazon S3 Transfer Acceleration==** allows you to generate a special URL that can be used by end users to upload files to a nearby Edge Location. Once a file is uploaded to an Edge Location, it can move much faster within the AWS Network to reach S3. 

### AWS Global Accelerator

\#aws-service   
![images/icons/Global_Accelerator_Icon.png](../../images/icons/Global_Accelerator_Icon.png)  
**==AWS Global Accelerator==** can find the optimal path from the end user to your web-servers. Global Accelerator are deployed within Edge Locations so you send user traffic to an Edge Location instead of directly to our web-application.
