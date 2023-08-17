---
title: 12-08 Standard vs Convertible RI
date: 08/11/23
---

There are some key differences between [Standard and Convertible RIs](12-03%20Reserved%20Instances.md#class)

|Standard RI|Convertible RI|
|-----------|--------------|
|RI attributes can be modified <br>- Change the AZ within the same Region<br>- Change the scope of the Zonal RI to Regional RI or visa versa<br>- Change the instance size (Linux/Unix only, default tenancy )<br>- Change network from Ec2-Classic to VPC and visa-versa|RI attributes CAN be modified|
|Can't be exchanged|Can be exchanged during the term for another <br>Convertible RI with new RI attributes, including:<br>- instance family<br>- instance type<br>- platform<br>- scope<br>- tenancy|
|Can be bought or sold in the RI Marketplace|Can't be bought or sold in the RI Marketplace|
