---
title: 22-09 Reliability Design Principles
date: 08/16/23
---

## Automatically recover from failure

Monitor Key Performance Indicators (KPIs) and trigger automation when a threshold is breached.

---

## Test recovery procedures

Test how your workload fails, and you validate your recovery procedures. You can use automation to simulate different failures or to recreate scenarios that led to failures before.

---

## Scale horizontally to increase aggregate system availability

Replace one large resource with multiple small resources to reduce the impact of a single failure on the overall workload. Distribute requests across multiple, smaller resources to ensure that they don’t share a common point of failure.

---

## Stop guessing capacity

In on-premise it takes a lot of guesswork to determine the elasticity of your workload demands. With Cloud, you don’t need to guess how much you need because you can request the right size of resources on-demand.

---

## Manage change in automation

Making changes via Infrastructure as Code will allow for a formal process to track and review infrastructure

---
