---
title: 25-09 Penetration Testing
date: 08/16/23
---

## What is PenTesting?

* An authorized simulated cyberattack on a computer system, performed to evaluate the security of the system.
* <span style="color:#98f792">Pen Testing **is allowed** to be performed on AWS!</span>

**Permitted Services**

* Amazon EC2 instances
* NAT Gateways
* Elastic Load Balancers
* Amazon RDS
* Amazon CloudFront
* Amazon Aurora
* Amazon API Gateways
* AWS Lambda and Lambda Edge functions
* Amazon Lightsail resources
* Amazon Elastic Beanstalk environments

**Prohibited Activities**

* DNS zone walking via Amazon Route 53 Hosted Zones
* Subject to the **DDoS Simulation Testing policy**
  * Denial of Service (DoS)
  * Distributed Denial of Service (DDoS)
  * Simulated DoS, Simulated DDoS
* Port flooding
* Protocol flooding
* Request flooding (login request flooding, API request flooding)

For **Other Simulated Events** you will need to submit a request to AWS. A reply could take up to 7 days.
