# Containerization-Deployment-of-Wisecow-
# Project Overview
This project demonstrates the containerisation, deployment, and automation (CI/CD) of the Wisecow Application — a simple bash-based web server that displays random quotes using the fortune and cowsay commands.
The app is Dockerized, deployed on Kubernetes, and integrated with GitHub Actions for continuous integration and deployment.
# Objectives
1. Containerize the Wisecow application using Docker
2. Deploy it to a Kubernetes environment (Minikube / Kind / Killercoda)
3. Automate the build & push process using GitHub Actions
4. Enable secure & accessible service exposure (port-based access)
# Repository Structure
```bash
wisecow/
├── wisecow.sh                 # Application script
├── Dockerfile                 # Docker image configuration
├── k8s/                       # Kubernetes manifests
│   ├── deployment.yaml
│   └── service.yaml
└── .github/workflows/
    └── ci-cd.yml              # GitHub Actions pipeline
```
# Features
- Dockerized Wisecow bash application
- Kubernetes manifests for deployment and service exposure
- Automated CI/CD pipeline that builds and pushes Docker images to DockerHub

