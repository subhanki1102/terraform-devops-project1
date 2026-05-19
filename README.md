# AWS DevOps Project using Terraform

## Project Overview

This project deploys a static website on AWS using:

- EC2
- NGINX
- Application Load Balancer (ALB)
- Terraform

The website is served through the ALB.

---

## Architecture

User → ALB → EC2 → NGINX → Static Website

---

## Resources Created

- VPC
- Public Subnets
- Internet Gateway
- Route Tables
- Security Groups
- EC2 Instance
- ALB
- Target Group
- Listener

---

## How to Run

### Initialize Terraform

terraform init

### Check Plan

terraform plan

### Deploy Infrastructure

terraform apply

---

## Validation

After deployment:

Open the ALB DNS name in browser.

Expected output:

Hello from AWS DevOps Assignment

---

## Security Best Practices

- Separate Security Groups
- EC2 accessible only through ALB
- Least privilege access
- No hardcoded secrets

---

## Screenshots

Add screenshots for:

- VPC
- EC2
- ALB
- Target Group
- Website
