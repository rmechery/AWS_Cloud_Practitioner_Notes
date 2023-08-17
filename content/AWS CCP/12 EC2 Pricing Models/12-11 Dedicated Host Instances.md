---
title: 12-11 Dedicated Host Instances
date: 08/11/23
---

[Dedicated Host Instances](https://aws.amazon.com/ec2/dedicated-hosts/) are designed to meet regulatory requirements.

When you have strict server-bound licensing that won’t support multi-tenancy or cloud deployments you use Dedicated Hosts.

## **Multi-tenant:** 

 > 
 > \[!example\] Example  
 > Think of everyone living in an apartment

* When multiple customers are running workloads on the same hardware.
* **Virtual Isolation** is what separate customers 

## **Single Tenant:** 

 > 
 > \[!example\] Example  
 > Think of everyone having their own house

When a single customer has dedicated hardware. **Physical Isolation** is what separates customers( Like a single-family home)

* Most expensive
* Use when you have strict **server-bound licensing** that won't support multi-tenancy or cloud deployments

Dedicated can be offered for:

* On-demand
* Reserved (up to 60% savings)
* Spot (up to 90% savings)

 > 
 > \[!note\] Note  
 > **Enterprises** and **Large Organizations** my have security concerns or obligations against sharing the same hardware with other AWS Customers
