# XOps Microchallenge #4 – Terraform + Ansible

## What this does
- Provisions an Ubuntu 22.04 t2.micro in `us-east-1` with Terraform
- Opens ports 22 (SSH) and 80 (HTTP)
- Uses Ansible to install NGINX and deploy `index.html`

## Prereqs
- AWS CLI configured (`aws configure`)
- Terraform, Ansible, SSH installed
- EC2 Key pair present in AWS (e.g., `xops-key`) and `.pem` on your machine (`chmod 400`)

## How to run

```bash
terraform init
terraform apply -auto-approve
# Note the public_ip output, then edit inventory
