---
title: 12-02 On Demand
date: 08/10/23
---

On-Demand is a **Pay-As-You-Go (PAYG)** model, where you consume compute and then you pay.

When you launch an EC2 instance it is ==by default== using [On-Demand](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-on-demand-instances.html) Pricing

* On-Demand has \*<i style="color:#f8857d">no up-front payment</i> and <i style="color:#f8857d">no long-term commitment</i>
* You are charged by the **hour** or by the **minute** (varies based on EC2 Instance Types
  * per-second for:
    * Linux, Windows, Windows with SQL Enterprise, Windows with SQL Standard, and Windows with SQL Web Instances that do not have a separate hourly charge
  * per-hour:
    * full hour for all other instance types.
* When looking up pricing it will always show EC2 pricing is the hourly rate
  * On-Demand is for applications where the workload is for **short-term, spikey,** or **unpredictable.**
  * Used for when you have a **new app** for development or you want to run an experiment
