---
title: 03-03 Fault Tolerance
date: 07/10/23
---

A ==Fault Domain== is a section of a network that is vulnerable to damage if a critical device or system fails. The purpose of a fault domain is that if a failure occurs <span style="color:#ff0000">it will not cascade outside that domain</span>, limiting the damage if possible.  ^1275f6

You can have fault domains nested fault domains. 

A ==fault level== is a collection of fault domains. ^d4ef9c

The scope of a fault domain could be:

* specific servers in a rack
* an entire rack in a datacenter
* the entire data center building   
  Its up to the [CSP](../01%20Cloud%20Concepts/01-02%20Cloud%20Service%20Provider%20CSP.md) to define the boundaries of a domain. 

E.g.   
an [AWS Region](03-01%20Global%20Infrastructure.md#regional-services) would be a [Fault Level](03-01%20Global%20Infrastructure.md#d4ef9c).  
an [Availability Zone](03-01%20Global%20Infrastructure.md#availability-zone) would be a [Fault Domain](03-01%20Global%20Infrastructure.md#1275f6).
