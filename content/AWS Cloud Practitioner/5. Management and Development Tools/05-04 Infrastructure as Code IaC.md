---
title: 05-04 Infrastructure as Code IaC
date: 07/10/23
---

* You write a configuration script to automate creating, updating or destroying cloud infrastructure.

* laC is a blueprint of your infrastructure.
* laC allows you to easily share, version or inventory your cloud infrastructure.

## AWS IaC Offerings

---

### AWS CloudFormation (CFN)

\#aws-service   
![images/icons/CloudFormation_Icon.png](../../images/icons/CloudFormation_Icon.png)  
CFN is a *Declarative* laC tool

* What you see is what you get. ***Explicit***
* More verbose, but zero chance of mis-configuration
* Uses scripting languages eg. JSON, YAML, XML

### AWS Cloud Development Kit (CDK)

\#aws-service   
![images/icons/CDK_Icon.png](../../images/icons/CDK_Icon.png)  
CDK is an *Imperative* laC tool.

* You say what you want, and the rest is filled in. ***Implicit***
* Less verbose, you could end up with misconfiguration
* Does more than Declarative
* Uses programming languages eg. Python, Ruby, JavaScript
