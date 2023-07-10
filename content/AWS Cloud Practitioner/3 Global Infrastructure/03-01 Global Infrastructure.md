---
title: 03-01 Global Infrastructure
date: 07/10/23
---

# Regions

Regions are ==geographically distinct locations== consisting of one more Availability Zones (AV).

 > 
 > \[!tip\]+ Key Facts  
 > US-EAST-1 (North Virginia) was the first region
 > 
 > * new services always become available here first  
 >   the cost of AWS services varies by region

## When you choose a region there are four factors to consider?

1. What regulatory compliance does this region meet?
1. What is the cost of AWS in this region?
1. What AWS services are available in this region?
1. What is the distance or latency to my end users?

## Regional vs. Global

### Regional Services

AWS <span style="color:#ff0000">scopes</span> their AWS Management console on a selected region.   
This will determine *where* an AWS service will be launched and what will be seen in the console.

### Global Services

Some AWS services operate across multiple regions and the region will be fixed to "Global"  
E.g. [Amazon S3](../8.%20Storage/08-02%20Introduction%20to%20S3.md), [CloudFront](03-04%20Point%20of%20Presence%20PoP.md#d7096a), Route53, IAM
