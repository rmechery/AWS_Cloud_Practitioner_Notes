---
title: 13-11 AWS IAM
date: 08/14/23
---

## AWS Identity and Access Management (IAM)

\#aws-service   
![35](images/icons/IAM_Icon.png) **AWS Identity and Access Management (IAM)** lets you create and manage AWS users and groups, and use permissions to allow and deny these users access to AWS resources.

### **IAM Policies**

JSON documents that grant permissions for a specific user, group, or role to access services. Policies are attached to **IAM Identities**

### **IAM Permission**

The API actions that can or cannot be performed. They are represented in the IAM Policy document

---

## **IAM Identities**

### **IAM Users**

End users who log into the console or interact with AWS resources programmatically or via clicking UI interfaces

### **IAM Groups**

Group up your Users so they all share permission levels of the group eg. Administrators, Developers, Auditors

### **IAM Roles**

Roles grant AWS resources permissions to specific AWS API actions Associate policies to a Role and then assign it to an AWS resource
