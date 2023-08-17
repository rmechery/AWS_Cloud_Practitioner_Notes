**Savings Plans** offer you similar discounts as [Reserved Instances (RI)](12-03%20Reserved%20Instances.md) **but simplifies the purchasing process**

You can choose two different terms

* **1 Year**
* **3 Year**

You choose the following Payment Options:

* All Upfront
* Partial Upfront
* No Upfront

## AWS Savings Plan Types

AWS Savings Plan has 3 different savings types:

### **Compute**

## Compute

\#aws-category   
![35](images/icons/Compute_Icon.png) Allows users to rent virtual computers on which to run their own computer applications.

* Compute Savings Plans provide the most flexibility and help to reduce your costs by up to 66%. 
* These plans automatically apply to EC2 instance usage, AWS Fargate, and AWS Lambda service usage regardless of instance family, size, AZ, region, OS, or tenancy.

### **EC2 Instances**

![35](../../images/icons/EC2_Icon.png) **Elastic Compute Cloud (EC2)** allows you to launch <span style="color:#ff0000">Virtual Machines (VM)</span>
  
\#aws-service  ^259d24

## What is a Virtual Machine?

A Virtual Machine (VM) is an emulation of a physical computer using software.  
Server Virtualization allows you to easily ==create, copy, resize or migrate== your server.  
Multiple VMs can run <span style="color:#ff0000">on the same physical server</span> so you can share the cost with other customers.  
*Imagine if your server or computer was an executable file on your computer*

When we launch a virtual machine we call it an "instance"

# Amazon Machine Image (AMI)

\#aws-resource   
![35](../../images/icons/AMI_Icon.png) EC2 is ==highly configurable== where you can choose an **amazon machine image (AMI)** that affects options such as:

* the amount of CPUs
* the amount of memory
* the amount of network bandwith
* the operation system (OS) eg. Windows 10, Ubuntu, Amazon Linux 2
* Attach multiple virtual hard-drives for storage eg. Elastic Block Store (EBS)

## Why is EC2 the backbone of AWS?

EC2 is also considered <span style="color:#ff0000">the backbone of AWS</span> because the majority of AWS services use EC2 as the underlying server  
eg. S2, RDS, DynamoDB, Lambdas

* provide the lowest prices, offering savings up to 72% in exchange for commitment to usage of individual instance families in a region. 
* automatically reduces your cost on the selected instance family in that region regardless of AZ, size, OS or tenancy. 
* give you the flexibility to change your usage between instances within a family in that region.

### **SageMaker**

## Amazon SageMaker

\#aws-service   
![75](images/icons/SageMaker_Icon.png)  
**Amazon SageMaker** is a fully managed service to **build, train, and deploy machine learning models** at scale

* **Apache MXNet on AWS**, open-source deep learning framework
* **TensorFlow on AWS** open-source machine intelligence library
* **PyTorch on AWS** open-source machine learning framework

* Helps you reduce SageMaker costs by up to 64%. 
* automatically apply to SageMaker usage regardless of instance family, size, component, or AWS region.
