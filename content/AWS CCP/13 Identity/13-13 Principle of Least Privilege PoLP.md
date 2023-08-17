---
title: 13-13 Principle of Least Privilege (PoLP)
date: 08/14/23
---

**Principle of Least Privilege (PoLP)** is the computer security concept of providing a user, role, or application the least amount of permissions to perform an operation or action.

## Just-Enough-Access (JEA)

Permitting only the exact actions for the identity to perform a task

## Just-In-Time (JIT)

Permitting the smallest length of duration an identity can use permissions

 > 
 > \[!example\]- Example
 > 
 > **ConsoleMe** is an open-source Netflix project to self-serve short-lived IAM policies so an end-user can access AWS resources while enforcing JEA and JIT  
 > [https://github.com/Netflix/consoleme](https://github.com/Netflix/consoleme)

## Risk-based adaptive policies

Each attempt to access a resource generates a risk score of how likely the request is to be from a compromised source. The risk score could be based on many factors e.g. device, user location, IP address what service is being accessed, and when.

 > 
 > \[!note\] Note  
 > AWS at the time of this recording does not have Risk-based adaptive policies built into IAM
