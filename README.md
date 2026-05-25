# GKE DevOps Task

This project demonstrates automated deployment of a containerized web application to Google Kubernetes Engine (GKE) using Terraform, Docker, Kubernetes, and GitHub Actions.

## Tech Stack

- Google Kubernetes Engine (GKE)
- Terraform
- Docker
- Kubernetes
- GitHub Actions
- Nginx

---

## Infrastructure Provisioning

Terraform was used to provision:

- GKE Cluster
- Node Pool
- Networking resources

### Run Terraform

```bash
terraform init
terraform plan
terraform apply