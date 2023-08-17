---
title: 25-19 AWS Key Management Service (KMS)
date: 08/16/23
---

## AWS Key Management Service (KMS)

![35](images/icons/KMS_Icon.png) **AWS Key Management Service (KMS)** is a managed service that makes it easy for you to create and control the encryption keys used to encrypt your data.

* KMS is a multi-tenant HSM (hardware security module)
* Many AWS services are integrated to use KMS to encrypt your data with a simple checkbox
* KMS uses Envelope Encryption.

## Envelope Encryption

* When you encrypt your data, your data is protected, but you have to protect your encryption key.
* When you encrypt your data key with a master key as an additional layer of security.

````mermaid
flowchart TD
	A[fa:fa-key KMS Master Key] -->|Encrypts| B[fa:fa-key fas:fa-envelope Envelope Data Key]
	B -->|Encrypts| C[fa:fa-database Data]
````
