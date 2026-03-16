# Terraform AWS EKS Infrastructure

This project provisions a production-ready AWS EKS (Elastic Kubernetes Service) cluster using Terraform.

## Architecture

Infrastructure includes:

* AWS VPC
* Public and Private Subnets
* Internet Gateway
* NAT Gateway
* AWS EKS Cluster
* Worker Node Groups
* IAM Roles and Policies
* Security Groups

## Tools Used

* Terraform
* AWS
* Kubernetes
* GitHub

## Project Structure

modules/

* vpc
* eks
* security-groups

## Deployment Steps

Initialize Terraform

terraform init

Review infrastructure plan

terraform plan

Deploy infrastructure

terraform apply

## Author

Charan
DevOps / Cloud Engineer
