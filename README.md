# 🚀 CI/CD Pipeline: GitHub Actions + Docker + AWS ECS

![CI/CD Pipeline](https://github.com/Vinutha1621/github-actions-cicd.git)

## 📌 Overview
End-to-end automated CI/CD pipeline that tests, builds, and deploys 
a containerized Python application to AWS ECS Fargate on every code push.

## 🏗️ Architecture
Code Push → GitHub Actions → Unit Tests → Docker Build → 
AWS ECR → AWS ECS (Fargate) → Live Application

## 🛠️ Tech Stack
- **CI/CD:** GitHub Actions
- **Containerization:** Docker
- **Container Registry:** AWS ECR
- **Orchestration:** AWS ECS Fargate
- **Language:** Python (Flask)
- **Testing:** Pytest

## ⚙️ Pipeline Stages
| Stage | Description |
|-------|-------------|
| ✅ Test | Runs unit tests with Pytest |
| 🐳 Build | Builds Docker image & pushes to ECR |
| 🚀 Deploy | Updates ECS task definition & deploys |

## 🔐 Secrets Required
- `AWS_ACCESS_KEY_ID`
- `AWS_SECRET_ACCESS_KEY`  
- `AWS_REGION`
