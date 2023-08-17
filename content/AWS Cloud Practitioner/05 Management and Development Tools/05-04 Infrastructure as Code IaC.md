---
title: 05-04 Infrastructure as Code (IaC)
date: 08/16/23
---

You write a configuration script to automate creating, updating, or destroying cloud infrastructure.

* IaC is a blueprint of your infrastructure.
* IaC allows you to easily share, version, or inventory your cloud infrastructure.

AWS has two offerings for writing Infrastructure as Code.

## AWS CloudFormation (CFN)

\#aws-service   
![75](images/icons/CloudFormation_Icon.png)  
CFN is a *Declarative* IaC tool

 > 
 > \[!abstract\] Declarative Definition
 > 
 > * You say what you want, and the rest is filled in. Explicit
 > * More verbose, but zero chance of misconfiguration
 > * Uses scripting languages eg. JSON, YAML, XML

## AWS Cloud Development Kit (CDK)

\#aws-service   
CDK is an *Imperative* IaC tool.

 > 
 > \[!abstract\] Imperative Definition
 > 
 > * What you see is what you get.  Implicit
 > * Less verbose, you could end up with misconfiguration
 > * Does more than Declarative
 > * Uses programming languages eg. Python, Ruby, JavaScript
