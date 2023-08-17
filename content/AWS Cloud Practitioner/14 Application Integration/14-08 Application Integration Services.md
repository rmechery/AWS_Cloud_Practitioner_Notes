---
title: 14-08 Application Integration Services
date: 08/15/23
---

![35](images/icons/SNS_Icon.png) **Simple Notification Service (SNS)** - a **pub-sub messaging system**. Sends notifications via various formats such as Plain-text **Email**, HTTP/s (**webhooks**) SMS (**text messages**), **SQS** and **Lambda**. Push messages which then are sent to subscribers

![35](images/icons/SQS_Icon.png) **Simple Queue Service (SQS)** is a queueing messaging service. Send events to a queue. Other applications pull the queue for messages. Commonly used for background jobs.

![35](images/icons/Step_Functions_Icon.png) **Step Functions** is a **state machine service**. It coordinates multiple AWS services into serverless workflows. Easily share data among Lambdas. Have a group of lambdas wait for each other. Create logical steps. Also works with Fargate Tasks.

![35](images/icons/EventBridge_Icon.png) **EventBridge (CloudWatch Events)** is a **serverless event bus** that makes it easy to connect applications together from your own application, third-party services, and AWS services.

![35](images/icons/Kinesis_Icon.png) **Kinesis** is a **real-time streaming data service**. Create **Producers** which send data to a stream. **Multiple Consumers** can consume data within a stream. Use for real-time analytics, click streams, ingesting data from a fleet of IoT Devices

![35](images/icons/MQ_Icon.png) **Amazon MQ** is a **managed message broker service** that uses **Apache ActiveMQ**

![35](images/icons/MSK_Icon.png) **Managed Kafka Service (MSK)** a **fully managed Apache Kafka service**. Kafka is an open-source platform for building real-time streaming data pipelines and applications. Similar to Kinesis but more robust

![35](images/icons/API_Gateway_Icon.png) **API Gateway** is a fully-managed service for developers to create, publish, maintain, monitor, and secure APIs. You can create API endpoints and route them to AWS services.

![35](images/icons/AppSync_Icon.png) **AppSync** is a **fully managed GraphQL service**. GraphQL is an open-source agnostic query adaptor that allows you to query data from many different data sources.
