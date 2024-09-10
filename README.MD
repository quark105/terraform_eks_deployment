# EKS Cluster Terraform Configuration

This repository contains Terraform configuration files for setting up an Amazon EKS (Elastic Kubernetes Service) cluster in AWS.

## Overview

This configuration deploys an EKS cluster with the following resources:
- VPC (Virtual Private Cloud)
- Subnets (Public, Private, Intra)
- EKS Cluster with CoreDNS, kube-proxy, and VPC CNI plugins
- EKS Managed Node Group with Spot Instances

## Prerequisites

- **Terraform**: Ensure you have Terraform installed. You can download it from [Terraform's official website](https://www.terraform.io/downloads).
- **AWS Credentials**: Set up your AWS credentials using environment variables, AWS CLI configuration, or IAM roles.

## Configuration

1. **Clone the Repository**

   ```bash
   git clone https://github.com/quark105/terraform_eks_deployment
   cd /terraform_eks_deployment
