# 🚀 End-to-End CI/CD Pipeline on AWS

This project demonstrates a complete CI/CD pipeline for automating build, test, Docker image creation, and deployment on AWS.

## 🛠 Tech Stack
- Jenkins
- Docker
- GitHub
- AWS EC2
- Linux (Shell Scripting)

## 📌 Architecture Overview
- Developer pushes code to GitHub
- Jenkins triggers pipeline automatically
- Application is built and Docker image is created
- Image is deployed to AWS EC2
- Zero manual intervention in deployment

## ⚙️ Features
- Automated build and deployment
- Dockerized application for consistency
- Reduced deployment errors and configuration drift
- Production-like CI/CD workflow

## 📈 Key Outcomes
- Reduced manual deployment effort by ~40%
- Improved deployment consistency across environments
- Faster release cycles

## 📂 Repository Structure
```text
├── Jenkinsfile
├── Dockerfile
├── scripts/
├── src/
└── README.md
🚀 How to Run

Clone the repository

Configure Jenkins and GitHub webhook

Run pipeline

Application deploys automatically on AWS EC2

📌 Author

Rajaneesh Hebballi
DevOps Engineer | AWS | Docker | Kubernetes
