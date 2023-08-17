---
title: 22-05 General Design Principles
date: 08/15/23
---

## Stop guessing your capacity needs

eg. Cloud computing you use as little or much-based **on demand**.

---

## Test systems at production scale

eg.  Clone production env to testing, Teardown testing not in use to save money.

---

## Automate to make architectural experimentation easier

eg. Using CloudFormation with ChangeSets, StackUpdate, and Drift Detection

---

## Allow for evolutionary architectures

eg. CI/CD, rapid or nightly releases, Lambdas deprecating run-times forcing you to evolve

---

## Drive architectures using data

eg. CloudWatch, Cloud Trail automatically turned on collecting data

---

## Improve through game days

eg. simulate traffic on production or purposely kill EC2 instances to see test recovery

---
