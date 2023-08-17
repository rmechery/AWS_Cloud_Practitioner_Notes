---
title: 11-02 EC2 Instance Families
date: 08/10/23
---

## What are Instance Families?

* Instance families are different combinations of CPU, Memory, Storage and Networking capacity. ^8eb238
* Instance families allow you to choose the appropriate combination of capacity to meet your application’s unique requirements.
* Different instance families are different because of the varying hardware used to give them their unique properties.
* Commonly instance families are called “Instance Types” but an instance type is a combination of size and family.

## Instance Families

### General Purpose

<span style="color:#98fafd">A1 T2 T3 T3a T4g M4 M5 M5a M5n M6zn M6g M6i Mac</span> 

* balance of compute, memory and networking resources
* **Use-cases** web servers and code repositories

---

### Compute Optimized

<span style="color:#98fafd">C5 C4 Cba C5n C6g C6gn  </span>

* Ideal for compute-bound applications that benefit from high-performance processor
* **Use-cases** scientific modeling, dedicated gaming servers, and ad server engines

---

### Memory Optimized

<span style="color:#98fafd">R4 R5 R5a R5b R5n X1 X1e High Memory z1d  </span>

* fast performance for workloads that process large data sets in memory.
* **Use-cases** in-memory caches, in-memory databases, real time big data analytics

---

### Accelerated Optimized

<span style="color:#98fafd">P2 P3 P4 G3 G4ad G4dn F1 Inf1 VT1  </span>

* hardware accelerators, or co-processors
* **Use-cases** Machine learning, computational finance, seismic analysis, speech recognition

---

### Storage Optimized

<span style="color:#98fafd">I3 I3en D2 D3 D3en H1</span>

* high, sequential read and write access to very large data sets on local storage
* **Use-cases** NoSQL, in-memory or transactional databases, data warehousing
