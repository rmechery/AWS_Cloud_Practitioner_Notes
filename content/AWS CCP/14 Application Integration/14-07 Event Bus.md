---
title: 14-07 Event Bus
date: 08/15/23
---

## What is an Event Bus?

* An event bus **receives events** from a **source** and **routes events** to a **target** based on **rules**

![700](images/14_Application_Integration/14-07/14-07_Event_Bus.png)

## EventBridge

\#aws-service   
![35](images/icons/EventBridge_Icon.png)  
**EventBridge** is a **serverless** event bus service that is used for application integration by **streaming real-time** data to your applications

 > 
 > \[!note\] Note  
 > **EventBridge** was formerly called **Amazon CloudWatch** Events.

![700](images/14_Application_Integration/14-07/14-07_EventBridge.drawio.svg)

### Event Bus

Holds event data, defines rules on an event bus to react to events.  
**Default Event Bus** — An AWS account has a default event bus  
**Custom Event Bus** — Scoped to multiple accounts or other AWS accounts  
**SaaS Event Bus** — Scoped to with Third-party SaaS Providers

### Producers

AWS Services that emit events

### Partner Sources

Are third-party apps that can emit events to an event bus

### Rules

Determines what events to capture and pass to targets. (100 Rules per bus)

### Targets

AWS Services that consume events (5 targets per rule)

### Events

Data emitted by services. JSON objects that travel (stream) within the event bus.
