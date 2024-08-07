---
title: 10-06 Other Database Services
date: 07/10/23
---

## Redshift

\#aws-service   
![35](images/icons/Redshift_Icon.png) **Redshift** is a petabyte-size data-warehouse. 

* Data-warehouses are for Online Analytical Processing (OLAP).
* Data-warehouses can be expensive because they are keeping data "hot"
  * Meaning that we can run a very complex query and a large amount of data and get that data back very fast

## ElastiCache

\#aws-service   
![35](images/icons/ElastiCache_Icon.png)  **ElastiCache** is a managed database of the *in-memory* and *caching* open-source databases

* ==Redis== or ==Memcached==

 > 
 > \[!abstract\] Purpose  
 > *When you need to improve the performance of an application by adding a caching layer in-front of a web-server or database*

## Neptune

\#aws-service   
![35](/images/icons/Neptune_Icon.png) **Neptune** is a managed graph database. 

* Database is represented as interconnected nodes

 > 
 > \[!abstract\] Purpose  
 > *When you need to understand the connections between data*

 > 
 > \[!example\]  Example  
 > Mapping Fraud Rings or Social Media Relationships

## Amazon Timestreams

\#aws-service   
![35](images/icons/Timestream_Icon.png) **Amazon Timestreams** is a fully managed time series database. 

* Think of devices that send lots of data that are time-sensitive such as IoT devices.
* When you need to measure how things change over time. 

## Amazon Quantum Ledger Database

\#aws-service   
![35](images/icons/Quantum_Ledger_Database_Icon.png)  **Amazon Quantum Ledger Database** is a fully managed ledger database that provides transparent, immutable and cryptographically variable transaction logs.

 > 
 > \[!abstract\] Purpose  
 > When you need to record history of financial activities that can be trusted.

## Database Migration Service (DMS)

\#aws-service   
![35](images/icons/Database_Migration_Service.png) **Database Migration Service (DMS)** is a database migration service. You can migrate from:

* on-premise database to AWS
* from two databases in different or same AWS accounts using different SQL engines
* from an SQL to NoSQL databases
