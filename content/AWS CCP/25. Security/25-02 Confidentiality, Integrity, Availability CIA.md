---
title: 25-02 Confidentiality, Integrity, Availability (CIA)
date: 08/16/23
---

Confidentiality, Integrity, and Availability (CIA) triad is a model describing the foundation of security principles and their trade-off relationship.

---

## Confidentiality

confidentiality is a component of privacy that implements to protect our data from unauthorized viewers. In practice, this can be using cryptographic keys to encrypt our data and using keys to encrypt our keys (envelope encryption)

## Integrity

maintaining and assuring the accuracy and completeness of data over its entire lifecycle. In Practice utilizing ACID-compliant databases for valid transactions. Utilizing tamper-evident or tamper-proof Hardware security modules. (HSM)

## Availability

information needs to be made be available when needed In Practice: High Availability, Mitigating DDoS, Decryption access

---

The CIA triad was first mentioned in a **NIST publication from 1977**.

There have been efforts to expand and modernize or suggest alternatives to CIA triad:

* (1998) Six Atomic Elements of Information eg. confidentiality, possession, integrity, authenticity, availability, and utility
* (2004) NIST Engineering Principles for Information Technology Security — 33 security principles
