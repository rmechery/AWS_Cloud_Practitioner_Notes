IAM Policies are written in JSON, and contain the permissions which determine what API actions are allowed or denied.

````json
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "Deny-Barclay-S3-Access",
      "Effect": "Deny",
      "Action": "s3:*",
      "Principal": {"AWS":["arn:aws:tam:123456789012:barclay"]},
      "Resource": "arn:aws:s3:::my-bucket"
    },
    {
      "Effect": "Allow",
      "Action": "iam:CreateServiceLinkedRole",
      "Resource": "*",
      "Condition": {
        "StringLike": {
          "iam: AWSServiceName": [
            "rds.amazonaws.com",
            "rds.application-autoscaling.amazonaws.com"
          ]
        }
      }
    }
  ]
}
````

* **Version policy language version**. 2012-10-17 is the latest version.
* **Statement container** for the policy element you are allowed to have multiples
* **Sid** (optional) a way of labeling your statements.
* **Effect** Set whether the policy will Allow or Deny
* **Action** list of actions that the policy allows or denies
* **Principal** account, user, role, or federated user to which you would like to allow or deny access
* **Resource** the resource to which the action(s) applies
* **Condition** (optional) circumstances under which the policy grants permission
