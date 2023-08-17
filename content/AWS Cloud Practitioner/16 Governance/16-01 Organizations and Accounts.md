---
title: 16-01 Organizations and Accounts
date: 08/15/23
---

## Organizations

\#aws-service   
![35](images/icons/Organizations_Icon.png) **Organizations** allow the creation of new AWS accounts. Centrally manage billing, control access, compliance, security, and share resources across your AWS accounts.

## Root Account User

\#aws-resource   
![35](images/icons/Root_Account_Icon.png)  
**Root Account User** is a single sign-in identity that has complete access to all AWS services and resources in an account. Each account has a Root Account User

## Organization Units

\#aws-resource   
![35](images/icons/Organizational_Unit_Icon.png)  
**Organization Units** are a group of AWS accounts within an organization which can also contain other organizational units - creating a hierarchy

## Service Control Policies

**Service Control Policies** give central control over the allowed permissions for all accounts in your organization, helping to ensure your accounts stay within your organization’s guidelines.

 > 
 > \[!note\] Note
 > 
 > * AWS Organizations must be turned on, once turned it cannot be turned off.
 > * You can create as many AWS Accounts as you like, one account will be the Master/Root Account
 > * AWS Account is <span style="color:#f8857d">not</span> the same as a User Account

![](images/16_Governance/16-01/16-01_Diagram.drawio.svg)
