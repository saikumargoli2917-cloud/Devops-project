# 🚀 DevOps CI/CD Pipeline with Docker & Kubernetes

![CI](https://github.com/saikumargoli2917-cloud/Devops-project/actions/workflows/ci.yml/badge.svg)

## 📌 Project Overview
...
This project demonstrates a complete end-to-end DevOps workflow by containerizing a web application using Docker, automating CI/CD using GitHub Actions, pushing Docker images to Docker Hub, and deploying the application on a Kubernetes cluster.

---

## 🧠 Architecture
Code → GitHub → CI/CD → Docker → Docker Hub → Kubernetes → Live Application

---

## ⚙️ Technologies Used
- Docker (Containerization)
- GitHub Actions (CI/CD Automation)
- Docker Hub (Container Registry)
- Kubernetes (Container Orchestration)
- Netlify (Web Deployment)
- HTML, Nginx

---

## 🧱 Features
- Automated CI/CD pipeline triggered on code push
- Docker image build and push to Docker Hub
- Secure credential management using GitHub Secrets
- Deployment to Kubernetes cluster using Deployment & Service
- Local access using port-forwarding
- Live deployment via Netlify

---

## 🐳 Docker Setup

### Build Docker Image
```bash
docker build -t sai-app .
