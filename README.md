

# AWS Platform Engineering Lab

A hands-on Platform Engineering and DevOps project demonstrating cloud infrastructure, Infrastructure as Code, containerisation, Kubernetes, CI/CD, automation, and AWS best practices.

## Project Goals

This project demonstrates practical experience with:

- AWS
- Terraform
- Docker
- Kubernetes
- Jenkins
- GitHub
- Python
- CI/CD
- Infrastructure as Code
- Cloud security
- Automation
- Monitoring and troubleshooting

## Architecture

The platform will progressively implement:

```text
GitHub
   |
   v
Jenkins CI/CD
   |
   +---- Build & Test
   |
   +---- Docker Image
   |
   v
Container Registry
   |
   v
Kubernetes
   |
   +---- Application
   |
   +---- Service
   |
   +---- Configuration
   |
   v
AWS Infrastructure

Terraform
   |
   +---- Infrastructure as Code

Python
   |
   +---- Automation

