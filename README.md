# AWS Highly Available Application Platform

## Overview

This project demonstrates a secure and highly available AWS application platform using Infrastructure as Code, configuration management, containerization, and automated CI/CD.

## Technology Stack

- AWS
- Linux
- Terraform
- Ansible
- Docker
- GitHub Actions
- Amazon ECR
- Application Load Balancer
- EC2 Auto Scaling
- Amazon RDS PostgreSQL
- AWS Secrets Manager
- Amazon CloudWatch

## Project Goals

- Deploy an application across multiple Availability Zones.
- Keep application and database resources in private subnets.
- Automate infrastructure provisioning with Terraform.
- Automate Linux configuration with Ansible.
- Build and deploy versioned Docker images.
- Implement CI/CD using GitHub Actions and AWS OIDC.
- Monitor application health and infrastructure metrics.
- Test instance replacement, deployment rollback, and recovery procedures.

## Security Principles

- Least-privilege IAM permissions.
- No permanent AWS access keys in GitHub Actions.
- No secrets committed to Git.
- Private application and database resources.
- Versioned container images.
- Restricted network access.
- Documented recovery procedures.
