# AWS-VPC-Peering-Project-
AWS VPC Peering Project

Project Overview

This project demonstrates private network connectivity between two Amazon VPCs using VPC Peering.

Architecture

- VPC A: "10.10.0.0/16"
- VPC B: "10.20.0.0/16"
- Bastion Host: "10.10.1.10"
- Private App A: "10.10.2.10"
- Private App B: "10.20.1.10"
- AWS Region: Mumbai ("ap-south-1")

AWS Services Used

- Amazon VPC
- EC2 Instances
- VPC Peering Connection
- Route Tables
- Security Groups
- Internet Gateway

Implementation

1. Created two VPCs with non-overlapping CIDR blocks.
2. Created subnets and launched EC2 instances.
3. Configured the Internet Gateway and route tables.
4. Established a VPC Peering connection.
5. Configured security groups for required traffic.
6. Tested SSH access and private connectivity.

Testing

Actual SSH and ping test results will be documented with screenshots. Connectivity is considered verified only when the corresponding test succeeds.

Evidence

See the "screenshots/" folder for AWS configuration screenshots and actual test outputs.

Security Note

Private keys, AWS credentials, and other secrets are not included in this repository.
