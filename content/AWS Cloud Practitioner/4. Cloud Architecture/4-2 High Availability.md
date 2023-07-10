---
title: 4-2 High Availability
date: 07/10/23
---

Your ability for your service to <span style="color:#ff0000">remain available</span> by ensuring there is <span style="color:#ff0000">\*no single point of failure</span> and/or ensure a certain level of performance

## Elastic Load Balancer

\#aws-service   
![images/icons/Elastic_Load_Balancing_Icon.png](../../images/icons/Elastic_Load_Balancing_Icon.png)

* A load balancer allows you to evenly distribute traffic to multiple servers in one or more datacenter. 
* If a datacenter or server becomes unavailable (unhealthy) the load balancer will route the traffic to only available datacenters with servers.

![450](../../images/3%20Global%20Infrastructure/4%20Cloud%20Architecture/High_Availability_Diagram.png)  
Running your workload across multiple Availability Zones ensures that if 1 or 2  
As become unavailable your service / applications remains available.
