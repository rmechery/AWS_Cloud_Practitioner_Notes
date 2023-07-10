---
title: 03-02 Availability Zone
date: 07/10/23
---

An <span style="color:#ff0000">Availability Zone (AV)</span> is a physical location made up of one or more data centers. 

A ==datacenter== is a secured building that contains hundreds of thousands of computers. ^b2786e

A ==region== will *generally* contain **3 Availability Zones**

Data-centers within a region will be isolated from each other (different buildings) but they will be close enough to provide low-latency (\< 10ms).

 > 
 > \[!tip\]+ Note  
 > Its common practice to run workloads in at least 3 AVs to ensure services remain available in case one or two data-centers fail. 

AZs are represented by a Region Code, followed by a letter identifier e.g. us-east-1<span style="color:#ff0000">a</span>

A ==Subnet== is associated with an Availability Zone.   
You never choose the the AZ when launching resources.  
You choose the Subnet which is associated to an AZ.
