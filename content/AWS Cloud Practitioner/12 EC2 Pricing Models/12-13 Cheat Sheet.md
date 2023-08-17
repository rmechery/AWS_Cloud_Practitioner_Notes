---
title: 12-13 Cheat Sheet
date: 08/11/23
---

* **[EC2 has 4 pricing models](https://aws.amazon.com/ec2/pricing/)**
  1. On-Demand
  1. Spot
  1. Reserved Instances (RI)
  1. Dedicated
* **[On-Demand](https://aws.amazon.com/ec2/pricing/on-demand/)** (Least commitment)
  * Low cost and flexible
  * Only pay per hour
  * Use Case: short-term, spiky, unpredictable workloads, and first time apps
  * Ideal when your workloads cannot be interrupted.
* **[Reserved Instances](https://aws.amazon.com/ec2/pricing/reserved-instances/)**- up to 75% off (Best long-term value)
  * **Use case:** steady state or predictable usage
  * Can resell unused reserved instances (Reserved Instance Marketplace)
  * Reduced Pricing is based on **Term x Class Offering x Payment Option**
  * **Payment Terms:** 1 year or 3 years
  * **Payment Options:** All Upfront, Partial Upfront, No Upfront
  * **Class Offerings:**
    * `Standard:` Up to 75% reduced pricing compared to on-demand. **Some attributes can be modified**
    * `Convertible:` Up to 54% reduced pricing compared to on-demand. **Some attributes can be modified**
    * NOTE: You cannot purchase Scheduled Reserved Instances at this time. AWS does not have any capacity available for Scheduled Reserved Instances or any plans to make it available in the future.
* **[Spot Pricing](https://aws.amazon.com/ec2/spot/)**- up to 90% off (Biggest Savings)
  * Request spare computing capacity
  * Flexible start and end times
  * **Use case:** Can handle interruptions like a server randomly stopping and starting
  * **Use case:** For non-critical background jobs
  * Instances can be terminated by AWS **at anytime**
  * If your instance is **terminated by AWS**, you don't get charged for a partial hour of usage.
  * If **you terminate** an instance you will still be charged for any hour that it ran.
* **[Dedicated Hosting](https://aws.amazon.com/ec2/dedicated-hosts/)** (Most Expensive)
  * Dedicated servers
  * Can be on-demand or reserved (up to 70% off)
  * **Use case**: When you need a guarantee of isolated hardware (enterprise requirements)
