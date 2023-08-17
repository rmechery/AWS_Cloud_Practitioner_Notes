---
title: 16-02 AWS Control Tower
date: 08/15/23
---

## AWS Control Tower

\#aws-service   
![35](../../images/icons/Control_Tower_Icon.png) **AWS Control Tower** helps <span style="color:#f8857d">Enterprises</span> quickly set-up a secure, **AWS multi-account**. Provides you with a **baseline environment** to get started with a **multi-account architecture**

### Landing Zone

A landing zone is a baseline environment following well-architected and best practices to start launching production ready workloads.

* AWS SSO enabled, Centralized logging for [20-02 AWS CloudTrail](../20%20Logging/20-02%20AWS%20CloudTrail.md), cross-account security auditing

### **Account Factory**

* automates provisioning of new accounts in your organization
* standardize the provisioning of new accounts with pre-approved account configurations
* configure your account factory with pre-approved network configuration and region selections
* enable self-service for your builders to configure and provision new accounts using AWS Service Catalog

### Guardrails

* pre-packaged governance rules for security, operations, and compliance that customers can select and apply enterprise-wide or to specific groups of accounts

 > 
 > \[!warning\] Note  
 > **AWS Control Tower** is the replacement for <span style="color:#f8857d">retired</span> **AWS Landing Zones**
