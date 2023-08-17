---
title: 12-05 Regional and Zonal RI
date: 08/10/23
---

When you purchase a RI, you determine the **scope** of the Reserved Instance.  
The scope <span style="color:#f8857d">does not affect the price</span>.

|Regional RI: purchase for a region|Zonal RI: purchase for an Availability Zone|
|----------------------------------|-------------------------------------------|
|does *not* reserve capacity|reserves capacity in the specified AZ|
|RI discount applies to instance  usage in any AZ in the Region|RI discount applies to instance in the  selected AZ (No AZ flexibility)|
|RI discount applies to instance usage  within the instance family, regardless  of size. Only supported on Amazon Linux/ Unix Reserved Instances with default tenacy.|No instance size flexibility. RI discount  applies to instance usage for the specified  instance type and size only.|
|You can queue purchases for regional RI||
