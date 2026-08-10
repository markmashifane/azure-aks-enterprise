# Azure AKS Enterprise Application

## Overview

This project demonstrates the deployment of a containerized Flask application to Microsoft Azure Kubernetes Service (AKS).

The application was developed locally, containerized with Docker, stored in Azure Container Registry (ACR), and deployed to an AKS cluster using Kubernetes manifests.

## Architecture

GitHub
↓
Flask Application
↓
Docker
↓
Azure Container Registry
↓
Azure Kubernetes Service (AKS)
↓
Kubernetes Deployment
↓
Kubernetes Pod
↓
Azure LoadBalancer
↓
Public Application

## Technologies Used

- Microsoft Azure
- Azure Kubernetes Service (AKS)
- Azure Container Registry (ACR)
- Docker
- Kubernetes
- Python
- Flask
- Azure CLI
- kubectl
- Git & GitHub

## Project Structure

```text
azure-aks-enterprise/
├── app/
│   ├── app.py
│   ├── Dockerfile
│   └── requirements.txt
├── k8s/
│   ├── deployment.yaml
│   └── service.yaml
├── .gitignore
└── README.md