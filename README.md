# AWS Infrastructure as Code (IaC) using CloudFormation

## Project Overview

This project demonstrates Infrastructure as Code (IaC) using AWS CloudFormation. The CloudFormation template automates the deployment of a Virtual Private Cloud (VPC), Amazon EC2 instances, an Elastic Load Balancer (ELB), and an Auto Scaling Group.

The template is reusable through parameters and provides outputs for easy access to deployed resources.

---

## AWS Services Used

- AWS CloudFormation
- Amazon VPC
- Amazon EC2
- Elastic Load Balancer (ELB)
- Auto Scaling Group

---

## Features

- Automated infrastructure deployment
- Parameterized CloudFormation template
- Reusable and customizable architecture
- Infrastructure consistency
- Easy deployment and management

---

## Repository Structure

```
AWS-CloudFormation-IaC/
└── LICENSE
├──README.md
├── cloudformation-template.yaml
├── deployment-guide.md
├── parameters.md

```

---

## Deployment Steps

1. Open AWS CloudFormation.
2. Create a new Stack.
3. Upload the CloudFormation template.
4. Enter the required parameters.
5. Review and create the stack.
6. Wait until the stack status becomes CREATE_COMPLETE.

---

## Expected Output

- VPC created
- EC2 Instance(s) launched
- Elastic Load Balancer configured
- Auto Scaling Group created

---

## Challenges Faced

- Understanding CloudFormation YAML syntax.
- Configuring infrastructure components correctly.
- Limited AWS resources prevented real deployment.

---

## Conclusion

CloudFormation simplifies infrastructure deployment by automating AWS resource provisioning while ensuring consistency and repeatability.
