# Deployment Guide

## Prerequisites

- AWS Account
- AWS CloudFormation
- EC2 Key Pair
- IAM permissions

---

## Deployment Steps

### Step 1

Login to the AWS Management Console.

### Step 2

Open CloudFormation.

### Step 3

Click **Create Stack**.

### Step 4

Upload the `cloudformation-template.yaml` file.

### Step 5

Provide the required parameters such as:

- VPC CIDR
- Subnet CIDR
- EC2 Instance Type
- Key Pair Name

### Step 6

Review the configuration.

### Step 7

Click **Create Stack**.

### Step 8

Wait until the stack reaches **CREATE_COMPLETE** status.

---

## Verification

Verify that the following resources have been created:

- VPC
- EC2 Instance
- Elastic Load Balancer
- Auto Scaling Group

---

## Cleanup

Delete the CloudFormation Stack to remove all associated AWS resources.
