---
title: 9-1 Cloud Networking Services
date: 07/10/23
---

![images/9 Networking/cloud_networking_services.drawio.svg](../../images/9%20Networking/cloud_networking_services.drawio.svg)

## **Key definitions:**

[**Region**](https://aws.amazon.com/about-aws/global-infrastructure/regions_az/) - the geographical location of your network

[**Availability Zone** (**AZ)**](https://aws.amazon.com/about-aws/global-infrastructure/regions_az/) - a data center containing your AWS resources

[**Virtual Private Cloud (VPC)**](https://docs.aws.amazon.com/vpc/latest/userguide/how-it-works.html)- a logically isolated section of the AWS Cloud where you can launch AWS resources

[**Internet Gateway**](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Internet_Gateway.html)- enables access to the Internet for your VPC

**[Route Tables](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Route_Tables.html)**- determines where network traffic from your subnets are directed

**[NACLs](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html)**- *Network Access Control Lists.* Act as a firewall at the subnet level

**[Security Groups](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_SecurityGroups.html)**- Act as firewall at the instance level

**[Subnets](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Subnets.html)**- a logical partition of an IP network into multiple, smaller network segments

## **Availability Zones:**

Availability Zones are the **data centers** where you launch your AWS resources into

Each AZs is associated with a specific `region`

## **Key VPC Components:**

A virtual private cloud (VPC) network is your own personal isolated section of the AWS cloud.

A `route table` contains a set of rules (called routes), that are used to determine where network traffic from your subnet or gateway is directed.

**Internet Gateway**- Allows you to grant internet access to resources inside of your VPC. But you also need a **route table** which routes the traffic from the VPC network out to the IGW

You can think of it as a door from your `VPC` outward.
