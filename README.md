# 🚀 DevOps Docker Project

![CI](https://github.com/saikumargoli2917-cloud/Devops-project/actions/workflows/ci.yml/badge.svg)
## 📌 Project Overview
This project demonstrates a simple DevOps workflow by containerizing a static web application using Docker and deploying it with Nginx.

## 🛠️ Technologies Used
- Docker
- Nginx
- HTML

## ⚙️ How It Works
1. Created a static web page (index.html)
2. Used Dockerfile to package the application
3. Deployed using Nginx inside a container

## 🚀 Run Locally

```bash
docker build -t sai-app .
docker run -p 80:80 sai-app
