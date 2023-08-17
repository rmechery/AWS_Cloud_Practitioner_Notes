---
title: 13-02 Zero Trust on AWS
date: 08/13/23
---

**Identity Security Controls** you can implement on AWS to meet the Zero Trust Model

## **AWS Identity and Access Management (IAM)**

<svg xmlns="http://www.w3.org/2000/svg" width="90" height="90" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-move-down"><path d="M8 18L12 22L16 18"/><path d="M12 2V22"/></svg>

* IAM Policies
* Permission Boundaries
* Service Control Policies (Organization-wide Policies)
* IAM Policy Conditions
  * `aws:SourceIp` – Restrict on IP Address
  * `aws:RequestedRegion` – Restrict on Region
  * `aws:MultiFactorAuthPresent` – Restrict if MFA is turned off
  * `aws:CurrentTime` – Restrict access based on time of day

<svg xmlns="http://www.w3.org/2000/svg" width="90" height="90" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-move-down"><path d="M8 18L12 22L16 18"/><path d="M12 2V22"/></svg>

## **Your AWS Resources**

 > 
 > \[!note\] Note  
 > AWS does not have ready-to-use identity controls that are intelligent, which is why AWS is considered to *not* have a true Zero Trust offering for customers, and third-party services need to be used.

---

A collection of AWS Services can be setup to intelligent-ish detection of identity concerns but requires expert knowledge

## **AWS CloudTrail**

![75](images/icons/CloudTrail_Icon.png)

* Tracks all API calls

## **Amazon GuardDuty**

![75](images/icons/GuardDuty_Icon.png)

* Detects suspicious or malicious activity based on CloudTrail and other logs

## **Amazon Detective**

\#aws-service   
![75](images/icons/Detective_Icon.png)

* Used to analyze, investigate and quickly identify security issues (can ingest findings from Guard Duty)
