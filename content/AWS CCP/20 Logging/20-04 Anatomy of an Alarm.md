---
title: 20-04 Anatomy of an Alarm
date: 08/15/23
---

![700](images/20-04_Anatomy_of_Alarm.png)

---

## Threshold Condition

Defines when a datapoint is breached

---

## Evaluation Periods

number of previous periods

---

## Data point

Represents the metric’s measurement at a given period

---

## Metric

The actual data we are measuring

---

## Period

How often it checks to evaluate the Alarm

---

## NetworkIn

The volume of incoming network traffic. measured in Bytes. When using 5min monitoring divide by 300 to get Bytes/second

---

## Datapoints to alarm

1 data point is breached in an evaluation period going back 4 periods. *This is what triggers the alarm*
