---
title: 20-03 CloudWatch Alarms
date: 08/15/23
---

<span style="color:#000000"></span>
**A CloudWatch Alarm** monitors a <span style="color:#f8857d">CloudWatch Metric</span> based on <span style="color:#f8857d">a defined threshold</span>.

When alarm breaches (goes outside the defined threshold) then it changes <span style="color:#f8857d">state</span>.

**Metric Alarm States**

* <b style="color:#98f792">OK</b> The metric or expression is **within** the defined threshold
* <b style="color:#ef857d">ALARM</b> The metric or expression is **outside** of the defined threshold
* <b style="color:#98fafd">INSUFFICIENT_DATA</b>

  * The alarm has just started
  * the metric is not available
  * Not enough data is available

When it changes state we can define what <span style="color:#f8857d">action it should trigger.</span>

* Notification
* Auto Scaling Group
* EC2 Action
