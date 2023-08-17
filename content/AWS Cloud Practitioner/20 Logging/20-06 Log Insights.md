---
title: 20-06 Log Insights
date: 08/15/23
---

**CloudWatch Logs Insights** enables you to **interactively search and analyze your CloudWatch log data** and has the following advantages:

* More robust filtering than using the simple Filter events in a Log Stream
* Less burdensome than having to export logs to S3 and analyze them via [Athena](../21%20ML,%20AI%20and%20Big%20Data/21-03%20Big%20Data%20and%20Analytics%20Services.md#2328c7).

**CloudWatch Logs Insights** supports all types of logs.

CloudWatch Logs Insights is commonly used via the console to do ad-hoc queries against logs groups.

CloudWatch Insights has its own language called:

* CloudWatch Logs Insights **Query Syntax**
* A single request can query up to **20 log groups.**
* Queries **time out after 15 minutes**, if they have not been completed.
* Query results are **available for 7 days.**

AWS provides sample queries that can get you started for common tasks,

And to ease learning the Query Syntax. A good example Is filtering VPC Flow Logs.

You can create and save your own queries to make future repetitive tasks easier.
