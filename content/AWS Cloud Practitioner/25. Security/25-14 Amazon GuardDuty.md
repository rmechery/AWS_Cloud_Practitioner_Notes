---
title: 25-14 Amazon GuardDuty
date: 08/16/23
---

## What is IDS/IPS?

* Intrusion Detection System and Intrusion Protection System.
* A device or software application that monitors a network or systems for malicious activity or policy violations.

## Amazon GuardDuty

\#aws-service   
![35](images/icons/GuardDuty_Icon.png) **GuardDuty** is a **threat detection service** that continuously monitors for malicious, suspicious activity and unauthorized behavior. It uses Machine Learning to analyze the following AWS logs:

* CloudTrail Logs
* VPC Flow Logs
* DNS logs

It will alert you of **Findings** which you can automate an incident response via CloudWatch Events or with 3rd Party Services
