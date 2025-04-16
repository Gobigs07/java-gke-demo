# java-gke-demo
# Java GKE CI/CD Demo

This is a simple Java Spring Boot application that demonstrates:
- CI/CD using GitHub Actions
- Docker containerization
- Kubernetes deployment on Google Kubernetes Engine (GKE)

## Features

- GitHub Actions pipeline for build/test/deploy
- Kubernetes manifests with ConfigMap, Secret, and Ingress
- Docker image pushed to Docker Hub

## Getting Started

```bash
mvn clean package
docker build -t Gobigs07/java-gke-demo .
