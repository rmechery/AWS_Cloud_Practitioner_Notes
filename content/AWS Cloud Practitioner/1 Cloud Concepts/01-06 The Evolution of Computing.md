---
title: 01-06 The Evolution of Computing
date: 07/10/23
---

## Dedicated

![200](../../images/1%20Computing/1-6%20Evolution%20of%20Computing/Dedicated_Diagram.png)

* A physical server <span style="color:#ff0000">wholly utilized by a single customer</span>.
* Must guess capacity.
* Overpay for an underutilized service.
* Can't vertical scale, need a manual migration.
* Replacing a server is very difficult.
* Limited by host operating system.
* Multiple apps can result in conflicts in resource sharing.
* You have full control over the server so <span style="color:#00ff00">you are guaranteed security, privacy, and full utility of underlying resources</span>.

## VMs

![300](../../images/1%20Computing/1-6%20Evolution%20of%20Computing/VMs_Diagram.png)

* You can run <span style="color:#ff0000">multiple Virtual Machines on one machine</span>.
* ==Hypervisor== is the software layer that lets you run the VMs.
* A physical server shared by multiple customers.
* You pay for a fraction of the server.
* You'll overpay for an underutilized Virtual Machine.
* Limited by Guest Operating System.
* Multiple apps can run into resource sharing conflicts.
* Easy to import/export images for migration.
* Easy to vertically or horizontally scale. 

## Containers

![300](../../images/1%20Computing/1-6%20Evolution%20of%20Computing/Containers_Diagram.png)

* Virtual machine running multiple containers
* ==Docker Daemon== is the name of the software layer that lets you run multiple containers.
* You can maximize the utility of the available capacity which is more cost-effective
* Your containers share the same underlying OS so containers are more efficient than multiple VMs
* Multiple apps can run side by side without being limited to the same OS requirements and will no cause conflicts during resource sharing. 

## Functions

![300](../../images/1%20Computing/1-6%20Evolution%20of%20Computing/Functions_Diagram.png)

* Are managed by VMs running managed containers
* Known as <span style="color:#ff0000">Serverless Compute</span><span style="color:#ff0000"></span>
* You upload a piece of code, choose the amount of memory and duration.
* Only responsible for code and data, nothing else
* Very cost-effective, only pay for the time code is running, VMs only run when there is code to be executed
* Cold Starts is a side-effect of this setup.
  * VM has to spin up so requests can be slow.
