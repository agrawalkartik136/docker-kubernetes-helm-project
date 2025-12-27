# Containerized Flask App on Kubernetes using Helm

## Project Overview
This project demonstrates containerization, orchestration, and deployment of a Flask application using Docker, Kubernetes, and Helm.

## Tech Stack
- Docker
- Kubernetes (Minikube)
- Helm
- Python (Flask)

## Architecture
- Docker image hosted on Docker Hub
- Kubernetes Deployment & Service
- Helm chart for release management

## Features
- Containerized application using Docker
- Kubernetes-based deployment and service exposure
- Horizontal scaling using replicas
- Rolling updates and rollbacks
- Helm-based release management

## Setup Instructions

### Build & Push Docker Image
```bash
docker build -t agrawalkartik136/my-flask-app:v1 .
docker push agrawalkartik136/my-flask-app:v1

## 🚀 CI/CD Pipeline
- Implemented CI using GitHub Actions to automatically build and push Docker images on every push to main
- Used Helm for Continuous Deployment to update Kubernetes workloads with new images
- This setup simulates a real-world DevOps workflow by separating CI automation and deployment management.

## 📸 Screenshots

### Application Running on Kubernetes
<<<<<<< HEAD:readme.md
[![App Running](screenshots/app-running.png)]

### Kubernetes Pods
[![Pods](screenshots/kubectl-get-pods.png)]

### Kubernetes Services
[![Services](screenshots/kubectl-get-svc.png)]

### Helm Release
[![Helm](screenshots/helm-release.png)]

