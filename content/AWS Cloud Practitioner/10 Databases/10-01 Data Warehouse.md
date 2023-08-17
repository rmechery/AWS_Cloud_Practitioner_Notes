---
title: 10-01 Data Warehouse
date: 07/10/23
---

![images/09_Networking/what_is_a_data_warehouse.drawio.svg](../../images/09_Networking/what_is_a_data_warehouse.drawio.svg)  
A relational datastore designed for ==analytic workloads==, which is generally ==column-oriented data-store==

Companies will have <mark style="background: #FF5582A6;">terabytes and million of rows of data</mark>, and they need a fast way to be able to produce analytics reports

Data warehouses generally perform **aggregation**:

* aggregation is *grouping data* eg. find a total or average
* Data warehouses are optimized around columns since they need to quickly aggregate column data

Data warehouses are generally designed to be HOT

* HOT means they can return queries very fast even though they have vast amounts of data

Data warehouses are infrequently accessed meaning they aren't intended for real-time reporting but maybe once or twice a day to generate business and user reports

A data warehouse needs to consume data from a relational database on a regular basis.

Note:  
ELT stands for Extract/Load/Transform(ELT) which is the process of extracting data from one or multiple sources and loading it into a target data warehouse.
