---
title: 04-04 High Elasticity
date: 07/10/23
---

Your ability to <span style="color:#ff0000">automatically</span> increase or decrease your capacity based on the current demand of traffic, memory and computing power

## Horizontal Scaling

1. Scaling Out - Add more servers of the same size <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-unfold-horizontal"><path d="M16 12h6"/><path d="M8 12H2"/><path d="M12 2v2"/><path d="M12 8v2"/><path d="M12 14v2"/><path d="M12 20v2"/><path d="m19 15 3-3-3-3"/><path d="m5 9-3 3 3 3"/></svg>
1. Scaling In - Removing underutilized servers of the same size <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-fold-horizontal"><path d="M2 12h6"/><path d="M22 12h-6"/><path d="M12 2v2"/><path d="M12 8v2"/><path d="M12 14v2"/><path d="M12 20v2"/><path d="m19 9-3 3 3 3"/><path d="m5 15 3-3-3-3"/></svg>

 > 
 > \[!tip\] Note  
 > Vertical Scaling is generally hard for traditional architecture so you'll usually only see **horizontal scaling** described with Elasticity.

## Auto Scaling Groups (ASG)

\#aws-service  
![75](images/icons/Auto_Scaling_Groups_Icon.png)  
An AWS feature that will automatically add or remove servers based on scaling rules you define based on metrics.
