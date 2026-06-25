# CloudFormation Parameters

| Parameter | Description |
|-----------|-------------|
| VpcCIDR | CIDR block for the VPC |
| PublicSubnetCIDR | CIDR block for the public subnet |
| InstanceType | EC2 instance type |
| KeyPairName | EC2 Key Pair |
| DesiredCapacity | Desired number of EC2 instances |
| MinSize | Minimum Auto Scaling Group size |
| MaxSize | Maximum Auto Scaling Group size |

---

# Outputs

The template returns the following outputs:

- VPC ID
- Public Subnet ID
- EC2 Instance ID
- Elastic Load Balancer DNS Name
- Auto Scaling Group Name

These outputs help identify the deployed AWS infrastructure after the CloudFormation stack is successfully created.
