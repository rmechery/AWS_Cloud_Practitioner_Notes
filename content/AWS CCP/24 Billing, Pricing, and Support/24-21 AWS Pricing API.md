---
title: 24-21 AWS Pricing API
date: 08/16/23
---

With AWS you can programmatically access pricing information to get the latest price offering for services.

There are two versions of this API:

* Query API – The Pricing Service API via JSON
* [https://api.pricing.us-east-1.amazonaws.com](https://api.pricing.us-east-1.amazonaws.com/)
* Batch API – The Price List API via HTML
* [https://pricing.us-east-1.amazonaws.com/offers/v1.0/aws/index.json](https://pricing.us-east-1.amazonaws.com/offers/v1.0/aws/index.json)

 You can also subscribe to [Amazon Simple Notification Service (Amazon SNS)](../14%20Application%20Integration/14-04%20Pub%20Sub.md#simple-notification-service-sns) notifications to get alerts when prices for the services change.

AWS prices change periodically, such as when AWS cuts prices when new instance types are launched, or when new services are introduced
