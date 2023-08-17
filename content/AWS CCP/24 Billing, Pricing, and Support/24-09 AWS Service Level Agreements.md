---
title: 24-09 AWS Service Level Agreements
date: 08/16/23
---

## DynamoDB SLA

AWS will use commercially reasonable efforts to make DynamoDB available with a Monthly Uptime Percentage for each AWS region, during any monthly billing cycle, of (a) at least 99.999% if the Global Tables SLA applies, or (b) at least 99.99% if the Standard SLA applies

In the event DynamoDB does not meet the Service Commitment, you will be eligible to receive a Service Credit as described below

<div>
<style type="text/css">
.tg  {border-collapse:collapse;border-color:#ccc;border-spacing:0;}
.tg td{background-color:#fff;border-color:#ccc;border-style:solid;border-width:1px;color:#333;
  font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{background-color:#f0f0f0;border-color:#ccc;border-style:solid;border-width:1px;color:#333;
  font-family:Arial, sans-serif;font-size:14px;font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-0lax"></th>
    <th class="tg-0lax">Monthly Uptime Percentage</th>
    <th class="tg-0lax">Service Credit Percentage</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0lax">Global Tables SLA</td>
    <td class="tg-0lax">Less than 99.999% but equal to or greater than 99.0%,<br>Less than 99.0% but equal to or greater than 95.0%,<br>Less than 95.0%</td>
    <td class="tg-0lax">10%,<br>25%,<br>100%</td>
  </tr>
  <tr>
    <td class="tg-0lax">Standard SLA</td>
    <td class="tg-0lax">Less than 99.99% but equal to or greater than 99.0%,<br>Less than 99.0% but equal to or greater than 95.0%,<br>Less than 95.0%</td>
    <td class="tg-0lax">10%,<br>25%,<br>100%</td>
  </tr>
</tbody>
</table>
</div>

---

## Compute SLAs

* Amazon Elastic Compute Cloud (Amazon EC2)\*
* Amazon Elastic Block Store (Amazon EBS)
* Amazon Elastic Container Service (Amazon ECS)
* AWS Fargate for Amazon ECS and Amazon EKS

AWS makes two SLA commitments for the Included Services:

1. a Region-Level SLA that governs Included Services deployed across multiple AZs or regions, and
1. an Instance-Level SLA that governs Amazon EC2 instances individually.

<div>
<style type="text/css">
.tg  {border-collapse:collapse;border-color:#ccc;border-spacing:0;}
.tg td{background-color:#fff;border-color:#ccc;border-style:solid;border-width:1px;color:#333;
  font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{background-color:#f0f0f0;border-color:#ccc;border-style:solid;border-width:1px;color:#333;
  font-family:Arial, sans-serif;font-size:14px;font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-0lax"></th>
    <th class="tg-0lax">Monthly Uptime Percentage</th>
    <th class="tg-0lax">Service Credit Percentage</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0lax">Region-Level SLA</td>
    <td class="tg-0lax">Less than 99.99% but equal to or greater than 99.0%, <br>Less than 99.0% but equal to or greater than 95.0%, <br>Less than 95.0%</td>
    <td class="tg-0lax">10%, <br>30%, <br>100%</td>
  </tr>
  <tr>
    <td class="tg-0lax">Instance-Level SLA</td>
    <td class="tg-0lax">Less than 99.5% but equal to or greater than 99.0%, <br>Less than 99.0% but equal to or greater than 95.0%,<br> Less than 95.0%</td>
    <td class="tg-0lax">10%,<br>30%, <br>100%</td>
  </tr>
</tbody>
</table>
</div>

---

## RDS SLA

AWS will use commercially reasonable efforts to make Multi-AZ instances available with a Monthly Uptime Percentage of at least 99.95% during any monthly billing cycle

In the event Amazon RDS does not meet the Monthly Uptime Percentage commitment, you will be eligible to receive a Service Credit as described below.

<div>
<style type="text/css">
.tg  {border-collapse:collapse;border-color:#ccc;border-spacing:0;}
.tg td{background-color:#fff;border-color:#ccc;border-style:solid;border-width:1px;color:#333;
  font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{background-color:#f0f0f0;border-color:#ccc;border-style:solid;border-width:1px;color:#333;
  font-family:Arial, sans-serif;font-size:14px;font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-0lax">Monthly Uptime Percentage</th>
    <th class="tg-0lax">Service Credit Percentage</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0lax">Less than 99.95% but equal to or greater than 99.0%, <br>Less than 99.0% but equal to or greater than 95.0%, <br>Less than 95.0%</td>
    <td class="tg-0lax">10%, <br>25%, <br>100%</td>
  </tr>
</tbody>
</table>
</div>
