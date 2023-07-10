---
title: 4-8 Disaster Recovery Options
date: 07/10/23
---

There are multiple options for recovery that trade cost vs time to recover.

|Backup & Restore|Pilot Light|Warm Standby|Multi-site Active/active|
|----------------|-----------|------------|------------------------|
|<span style="color:#0000ff">RPO/RTO ~ Hours</span>|<span style="color:#cd7ceb">RPO/RTO ~ 10mins</span>|<span style="color:#eb7c8b">RPO/RTO ~ minutes</span>|<span style="color:#ff0000">RPO/RTO ~ Real-time</span>|
|You backup your data and restore it to new infrastructure|Data is replicated to another region with minimal services running|Scaled down copy of your infrastructure running ready to scale up|Scaled up copy of your infrastructure in another region|
|• Lower priority use cases|• less stringent rpo|• business critical services|•  zero downtime|
|• Restore data after event|• core services|• scale resources after event|•   near zero loss|
|• deploy resources after event|• start & scale resources after event|• cost $$$|•  mission critical services|
|• cost $|• cost $$|•|• cost $$$$|
