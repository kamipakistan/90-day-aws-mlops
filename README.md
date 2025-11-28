# 90-Day Job-Ready MLOps Roadmap (AWS Focused)

This repository documents my **90-Day Job-Ready MLOps Challenge** — a structured, hands-on learning journey to become an industry-grade **MLOps Engineer** using AWS.

I will upload **daily learning logs, code, infrastructure files, and deployment projects** as I complete each task.

---

## Objective

To become proficient in:
- Deploying ML systems on AWS
- Automating ML pipelines
- Containerization using Docker
- CI/CD pipelines using GitHub Actions
- Production-grade monitoring and scaling
- Infrastructure as Code using Terraform
- Kubernetes deployments on AWS EKS

---

## Challenge Structure

This roadmap is organized into **three progressive phases**, each focused on building real-world MLOps capability.

Each phase clearly defines:
- What to learn (concepts & tools)
- What to build (hands-on projects)
- Portfolio-ready output (deployments, automation, infra)

---

## Roadmap Phases

| Phase | Focus Area | Goal |
|--------|------------|------|
| **Phase 1** | AWS, Linux & Docker | Build foundation for ML deployment |
| **Phase 2** | Containers & SageMaker | Deploy production ML systems |
| **Phase 3** | Production MLOps | Engineer scalable, automated ML pipelines |

---


# PHASE 1 (Days 1–30)
## AWS + Linux + Docker Foundations
> Goal: Manually deploy ML apps on AWS with confidence.

---

## Week 1 — AWS & Linux Basics

### Learn:
- IAM & Users
- EC2 instances
- Security Groups
- SSH Access
- Linux fundamentals
- Networking basics

### Tools:
- Amazon EC2
- AWS IAM
- Amazon VPC

### Practice:
- Launch EC2  
- SSH from local machine  
- Install Python, pip, git  
- Run a sample ML model manually

---

## Week 2 — Docker & Containers

### Learn:
- Dockerfile
- Image build & push
- Container run
- Networking basics for Docker

### Tools:
- Docker
- Amazon Elastic Container Registry (ECR)

### Practice:
- Dockerize ML API  
- Push image to ECR  
- Pull and run Docker image on EC2

---

## Week 3 — ML API Deployment

### Learn:
- FastAPI
- Gunicorn
- Nginx
- Environment variables
- Log handling

### Project #1 — ML API on EC2 (Dockerized)

**Stack:**
- FastAPI
- Docker
- AWS EC2
- Amazon ECR

**Expected Repo Structure:**

- /deploy
- /Dockerfile
- /requirements.txt
- /infra.md (architecture)


---

## Week 4 — CI/CD Basics

### Learn:
- GitHub workflows
- Build pipelines
- Deployment automation

### Tools:
- GitHub Actions

### Project #2 — Auto Deployment Pipeline

### Build:
- Docker image build pipeline  
- Push image to ECR  
- Auto-deploy to EC2 via SSH

Portfolio:
**Project #2: Auto Deployment Pipeline**

---

# PHASE 2 (Days 31–60)
## Containers & SageMaker
> Goal: Learn production-grade ML deployment.

---

## Week 5 — Container Orchestration (ECS)

### Learn:
- ECS tasks
- Auto scaling
- Load balancing
- Task definition

### Tools:
- Amazon ECS
- AWS Fargate

### Project #3 — ML API on ECS

---

## Week 6 — Data & Model Storage

### Learn:
- Object storage
- Versioning
- Dataset management

### Tools:
- Amazon S3

### Practice:
- Upload datasets  
- Store trained models  
- Version artifacts

---

## Week 7 — AWS SageMaker

### Learn:
- Training jobs
- Endpoints
- Model registry
- Pipelines

### Tool:
- Amazon SageMaker

### Project #4 — Full ML Lifecycle on SageMaker

---

## Week 8 — Monitoring & Logging

### Learn:
- Logging
- Metrics
- Alerting
- Latency monitoring

### Tool:
- Amazon CloudWatch

### Practice:
- Error alarms  
- CPU scaling  
- Request tracking

---

# PHASE 3 (Days 61–90)
## Production MLOps Engineering
> Goal: Operate at Senior MLOps level.

---

## Week 9 — Infrastructure as Code

### Learn:
- Environment provisioning
- Automation

### Tool:
- Terraform

### Project #5 — Fully Automated AWS Infrastructure

---

## Week 10 — Kubernetes & EKS

### Learn:
- Pods
- Services
- Ingress
- Helm

### Tools:
- Amazon EKS
- Kubernetes

---

## Week 11 — Model Versioning & Experiment Tracking

### Learn:
- Model tracking
- Experiment management
- Promotion workflows

### Tool:
- MLflow

---

## Week 12 — Final Capstone Project

### End-to-End Production System:
Includes:
- CI/CD Pipelines
- ECS or EKS deployment
- SageMaker training
- Terraform-managed infra
- Monitoring
- Model versioning

---

# FINAL PORTFOLIO

| Project | Skill Demonstrated |
|----------|------------------|
| ML API on EC2 | Infrastructure & Docker |
| CI/CD | DevOps |
| ECS Deployment | Cloud Engineering |
| SageMaker | MLOps |
| Terraform | Infrastructure Automation |
| Kubernetes | Enterprise-Grade Systems |

---

# Interview Focus Areas

- Linux  
- Docker  
- AWS Core Services  
- CI/CD  
- Monitoring  
- Model Lifecycle  
- Deployment Strategies  

---

# Optional Certifications (Future)

- AWS Cloud Practitioner  
- AWS Solutions Architect Associate  
- AWS Machine Learning Specialty  

---

# Daily Updates

Each day I will push:
- Code updates
- Documentation
- Architecture diagrams
- Mistakes & lessons learned

---
