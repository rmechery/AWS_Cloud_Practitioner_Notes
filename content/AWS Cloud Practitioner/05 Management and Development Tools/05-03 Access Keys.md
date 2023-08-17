---
title: 05-03 Access Keys
date: 07/10/23
---

Access Keys (aka AWS Credentials) is a ==key and secret== required to have programmatic access to AWS resources when interacting with the [AWS API](05-01%20AWS%20API.md) outside of the [AWS Management Console](05-01%20AWS%20API.md#aws-management-console).

 > 
 > \[!info\] Note  
 > A user must be granted access to use Access Keys

## Important Notes:

* Never share your access keys
* Never commit access keys to a codebase
* You can have two active Access Keys
* You can deactivate Access Keys
* Access Keys have whatever access a user has to AWS resources.

Access Keys are to be store in `~/.aws/credentials` and follow a TOML file format

````toml
[default]
aws_access_key_id=AKIAIOSFODNNTEXAMPLE
aws_secret_access_key=wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
[exampro]
aws_access_key_id=AKIAIOSFODNN7EXAMPLE
aws_secret_access_key=wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
region=ca-central-i
````

* <span style="color:#ff0000">Default</span> will be the access key used when no profile is specified.
* You can store multiple access keys by giving the profile names. ex. exampro

````bash session
$ aws configure
AWS Access Key ID [None]: AKIAIOSFODNN7EXAMPLE
AWS Secret Access Kev [Nonel: wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
Default region name [None]: us-west-2
Default output format [None]: json
````

* You can use the <span style="color:#ff0000">aws configure</span> CLI command to populate the credential file.

````bash session
$ export AWS ACCESS KEY ID=AKIAIOSFODNNTEXAMPLE
$ export AWS SECRET ACCESS KEY=wJalrxUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
$ export AWS DEFAULT REGION=us-west-2
````

* The AWS SDK will automatically read from these environment variables 
* This is the safe way of using an Access Key in your code.
