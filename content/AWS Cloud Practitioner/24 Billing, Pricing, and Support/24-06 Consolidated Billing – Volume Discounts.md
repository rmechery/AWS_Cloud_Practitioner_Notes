---
title: 24-06 Consolidated Billing – Volume Discounts
date: 08/16/23
---

* AWS has **Volume Discounts** for many services
* The more you use, the more you save.
* Consolidated Billing lets you take advantage of Volume Discounts
* Consolidate Billing is a feature of [AWS Organizations](../16%20Governance/16-01%20Organizations%20and%20Accounts.md#organizations)

 > 
 > \[!example\]+ Example
 > 
 > We got two users, <span style="color:#ef857d">Odo</span> and <span style="color:#98f792">Dax</span>.  
 > <span style="color:#ef857d">Odo</span> has transferred 4TB in a month.  
 > On the other hand, <span style="color:#98f792">Dax</span> has transferred 8TB in a month.
 > 
 > According to AWS, the first 10TB costs ¢17 per GB and every 40TB after costs ¢13 per GB. 
 > 
 > <span style="color:#ef857d">Odo</span> (4 \* 1024) \* 0.17 = $696.32  
 > <span style="color:#98f792">Dax</span>  (8 \* 1024) \* 0.17 = $1392.64
 > 
 > **Unconsolidated**            696.32+1392.64 = <span style="color:#ef857d">$2088.96</span>
 > 
 > **Consolidated**               ((10 \* 1024) \* 0.17)+((2 \* 1024) \* 0.13) = <span style="color:#98f792">$2007.04</span>
 > 
 > With an Consolidated Bill, you pay $81.92 less!
