# CloudFormation-EC2
AWS CloudFormation Template for Launching Two EC2 Instances

Overview
This CloudFormation template provisions two EC2 instances in a specified AWS region using a predefined AMI ID, VPC, Subnet, and Key Pair. The template supports parameterization to customize instance types and other configurations.

Features
Deploys two EC2 instances 
Allows customization of instance type, AMI, key pair, VPC, and subnet
Uses CloudFormation Outputs to retrieve Instance IDs after deployment

Notes
Ensure you have a valid AWS IAM Role with permissions to create EC2 instances.
The Key Pair must exist in the selected AWS region before deploying the stack.
The AMI ID should be compatible with your AWS region.
