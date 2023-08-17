---
title: 25-17 AWS WAF
date: 08/16/23
---

## AWS WAF

![35](images/icons/WAF_Icon.png) AWS **Web Application Firewall (WAF)** protect your web applications from common web exploits

* Write your own **rules** to ALLOW or DENY traffic based on the contents of HTTP requests
* Use a ruleset from a trusted AWS Security Partner in the AWS WAF Rules Marketplace
* WAF can be attached to either **CloudFront** or an **Application Load Balancer**

Protect web applications from attacks covered in the **OWASP Top 10** most dangerous attacks:

1. Injection
1. Broken Authentication
1. Sensitive data exposure
1. XML External Entities (XXE)
1. Broken Access control
1. Security misconfigurations
1. Cross-Site Scripting (XSS)
1. Insecure Deserialization
1. Using Components with known vulnerabilities
1. Insufficient logging and monitoring
