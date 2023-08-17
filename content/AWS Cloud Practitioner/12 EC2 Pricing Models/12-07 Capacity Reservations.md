---
title: 12-07 Capacity Reservations
date: 08/10/23
---

EC2 instances are backed by a different kind of hardware, and so there is a <mark style="background: #FFB86CA6;color:white"><b>finite amount of servers</b></mark> available within an Availability Zone per instance type or family.

 > 
 > \[!example\] Example  
 > You go to launch a specific type of EC2 instance but AWS has run out of that server!

**Capacity Reservation** is a service of EC2 that allows you to <mark style="background: #FFB86CA6;color:white"><b>request a reserve of EC2 instance type</b></mark> for a specific Region and AZ

The reserved capacity is charged at the selected instance type's On-Demand rate whether an instance is running or not. 

You can also use your regional reserved instances with your Capacity reservations to benefit from billing discounts.
