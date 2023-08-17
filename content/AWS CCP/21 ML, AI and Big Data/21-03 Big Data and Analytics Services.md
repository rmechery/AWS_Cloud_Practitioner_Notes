---
title: 21-03 Big Data and Analytics Services
date: 08/15/23
---

**What is BigData?**  
A term used to describe massive volumes of structured/unstructured data that is so large it is difficult to move and process using traditional database and software techniques.

![35](images/icons/Athena_Icon.png) **Amazon Athena** is a serverless interactive query service. It can take a bunch of CSV or JSON files in an S3 Bucket and load them into temporary SQL tables so you can run SQL queries. When you want to query CSV or JSON files. #aws-service  ^2328c7

**Amazon CloudSearch** is a fully managed full-text search service. When you want to add search to your website

**Amazon Elasticsearch Service (ES)** is a managed Elasticsearch cluster. Elasticsearch is an open-source full-text search engine. It is more robust than CloudSearch but requires more server and operational maintenance.

**Amazon Elastic MapReduce (EMR)** is for data processing and analysis. It can be used for creating reports just like Redshift but is more suited when you need to transform unstructured data into structured data on the fly.

**Kinesis Data Streams** is a real-time streaming data service. Create Producers which send data to a stream. Multiple Consumers can consume data within a stream. Use for real-time analytics, clickstreams, ingesting data from a fleet of IoT Devices

**Kinesis Firehose** is serverless and a simpler version of Data Streams, You pay on-demand based on how much data is consumed through the stream and you don’t worry about the underlying servers.

**Amazon Kinesis Data Analytics** allows you to run queries against data that is flowing through your real-time stream so you can create reports and analysis on emerging data.

**Amazon Kinesis Video Streams** allows you to analyze or apply processing on real-time streaming video.

**Managed Kafka Service (MSK)** a fully managed Apache Kafka service. Kafka is an open-source platform for building real-time streaming data pipelines and applications. It is similar to Kinesis but with more robust functionalities

**Redshift** is a petabyte-size data-warehouse. Data-warehouses are for Online Analytical Processing) OLAP Data-warehouses can be expensive because they are keeping data “hot”. Meaning that we can run a very complex query and a large amount of data and get that data back very fast. When you want to quickly generate analytics or reports from a large amount of data.

**Amazon QuickSight** is a business intelligence (BI) dashboard. You can use it to create business dashboards to power business decisions. It requires little to no programming knowledge, connects and ingests to many different types of databases

**AWS Data Pipeline** automates the movement of data. You can reliably move data between compute and storage services.

**AWS Glue** is an Extract, Transform, Load (ETL) service. Moving data from one location to another and where you need to perform transformations before the final destination. Similar to Database Migration Service (DMS) but more robust

**AWS Lake Formation** is a centralized, curated, and secured repository that stores all your data. A data lake is a storage repository that holds a vast amount of raw data in its native format until it is needed.

**AWS Data Exchange** is a catalog of third-party datasets. You can download for free subscribe or purchase datasets. Eg. COVID-19 Foot Traffic Data, IMDB TV and Movie data, Historical Weather Data
