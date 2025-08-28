# Terraform XOps Web Server

This project provisions an AWS EC2 instance inside a custom VPC, installs Apache, and serves a basic web page.

## Prerequisites
- AWS account
- Terraform CLI
- AWS CLI configured (`aws configure`)
- IAM user with AmazonEC2FullAccess & AmazonVPCFullAccess

## run
```bash
terraform init
terraform validate 
terraform plan
terraform apply -auto-approve
