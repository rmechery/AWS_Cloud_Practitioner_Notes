---
title: 14-02 Queuing
date: 08/14/23
---

## What is a Messaging System?

Used to provide asynchronous communication and decouple processes via messages/events From a sender and receiver ( producer and consumer)

## What is a Queueing System?

A Queueing system is a messaging system that generally will delete messages once they are consumed. Simple communication. <b style="color:#f8857d">Not Real-time</b>. Have to pull. Not reactive.

## Simple Queueing Service (SQS)

\#aws-service   
![35](images/icons/SQS_Icon.png) **Simple Queueing Service (SQS)** is a fully managed **queuing service** that enables you to decouple and scale microservices, distributed systems, and serverless applications

 > 
 > \[!example\] Use Case  
 > You need to queue up transaction emails to be sent e.g. Signup, Reset Password.
