---
title: 25-06 Digital Signatures and Signing
date: 08/16/23
---

## What is a digital signature?

* A mathematical scheme for verifying the authenticity of digital messages or documents.
* A Digital signature gives us **tamper-evidence**.
  * Did someone mess (modify) the data?
  * Is this data is not from the expected sender?

There are three algorithms for digital signatures:

* **Key generation** – generates a public and private key.

* **Signing** – the process of generating a digital signature with a **private key** and inputted message

* **Signing verification** – verify the authenticity of the message with a **public key**

* SSH uses a public and private key to authorize remote access into a remote machine e.g. Virtual Machine. It is common to use RSA

* `ssh-keygen -t rsa` is a **well-known command** to generate a public and private key

## What is Code Signing?

When you use a digital signature to ensure **computer code** has not been tampered
