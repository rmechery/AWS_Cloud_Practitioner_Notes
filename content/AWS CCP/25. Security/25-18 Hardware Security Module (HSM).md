---
title: 25-18 Hardware Security Module HSM
date: 08/16/23
---

## What is a Hardware Security Module (HSM)?

* It's a piece of hardware designed to store encryption keys.
* An HSM holds keys in memory and never writes them to disk.

## **Federal Information Processing Standard (FIPS)**

US and Canadian government standard that specifies the security requirements for cryptographic modules that protect sensitive information.

* HSM’s that are **multi-tenant** is **FIPS 140-2 Level 2 Compliant**
  * (multiple customers virtually isolated on an HSM)
  * eg. AWS KMS
* HSM’s that are **single-tenant** are **FIPS 140-2 Level 3 Compliant**
  * (single customer on a dedicated HSM)
  * eg. AWS CloudHSM
