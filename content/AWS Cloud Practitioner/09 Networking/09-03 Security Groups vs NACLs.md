---
title: 09-03 Security Groups vs NACLs
date: 07/10/23
---

![images/09_Networking/Security_Groups_vs_NACLS.png](../../images/09_Networking/Security_Groups_vs_NACLS.png)

## Network Access Control Lists (NACLs)

\#aws-resource 

* Acts as a virtual ==firewall at the subnet level.==
* You create <mark style="background: #FF5582A6;">Allow and Deny Rules</mark>. 
* eg. Block a specific IP address known for abuse.

## Security Groups

\#aws-resource 

* Acts as a virtual ==firewall at the instance level==.
* Implicitly denies all traffic.
* You create <mark style="background: #FF5582A6;">only Allow rules</mark>.
* eg. Allow an Ec2 instance access on port 22 for SSH
* Note: You cannot block a single IP address. 

|Security group|Network ACL|
|--------------|-----------|
|Operates at the instance level|Operates at the subnet level|
|Applies to an instance only if it is associated with the instance|Applies to all instances deployed in the associated subnet (providing an additional layer of defense if security group rules are too permissive)|
|Supports allow rules only|Supports allow rules and deny rules|
|Evaluates all rules before deciding whether to allow traffic|Evaluates rules in order, starting with the lowest numbered rule, when deciding whether to allow traffic|
|Stateful: Return traffic is allowed, regardless of the rules|Stateless: Return traffic must be explicitly allowed by the rules|

### Reference

[Security groups for your VPC](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_SecurityGroups.html)
