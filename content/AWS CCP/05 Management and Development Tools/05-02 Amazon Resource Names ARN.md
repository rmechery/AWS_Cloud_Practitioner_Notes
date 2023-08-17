---
title: 05-02 Amazon Resource Names ARN
date: 07/10/23
---

Amazon Resource Names (ARN) uniquely identify AWS resources.   
ARNs are required to specify a resource unambiguously across all of AWS.

ARNs follow any one of the formats below:

1. `arn:partition:service:region:account-id:resource-id`
1. `arn:partition:service:region:account-id:resource-type/resource-id`
1. `arn:partition:service:region:account-id:resource-type:resource-id`

## ARN Parts

### Partition

* `aws` - AWS Region
* `aws-cn` - China Regions
* `aws-us-gov` - AWS GovCloud(US) Regions

### Service

identifies the service

* `ec2`
* `s3`
* `iam`

### Region

which aws resource

* `us-east-1`
* `ca-central-1`

Account ID  
12 digit number ex.

* `012345678901`

Resource ID  
could be a number name or path:

* `user/Bob`
* `instance/i-123456789`
