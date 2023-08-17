---
title: 25-05 Hashing and Salting
date: 08/16/23
---

## What is hashing function?

* A function that accepts arbitrary size value and maps it to a fixed-size data structure. Hashing can reduce the size of the store value.
* Hashing is a **one-way process** and is **deterministic**
* A deterministic function always returns the same output for the same input.

## Hashing Passwords

* Hashing functions are used to store passwords in the database so that a password does not reside in a plaintext format.
* To authenticate a user, when a user inputs their password, it is hashed, and the hash is compared to the store hashed. If they match then the user has successfully logged in.
* Popular hashing functions are **MD5, SHA256, and Bcrypt**
* If an attacker knows what function you are using and stole your database, they could enumerate a dictionary of passwords to determine the password.

## Salting Passwords

A salt is a random string not known to the attacker that the hash function accepts to mitigate the deterministic nature of hashing functions
