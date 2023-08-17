---
title: 24-18 AWS Cost and Usage Reports (CUR)
date: 08/16/23
---

Generate a **detailed spreadsheet**, enabling you to better **analyze and understand your AWS costs**

* Places the reports into S3

* Use [Athena](../21%20ML,%20AI%20and%20Big%20Data/21-03%20Big%20Data%20and%20Analytics%20Services.md#2328c7) to turn the report into a queryable database

* Use [QuickSight](../21%20ML,%20AI%20and%20Big%20Data/21-04%20Amazon%20QuickSight.md) to visualize your billing data as graphs

* Choose the granularity of your data by selecting hourly, daily, or monthly

* The report will contain Cost Allocation Tags

* CUR data is stored in a CSV (GZIP) or Parquet format in your selected S3 bucket
