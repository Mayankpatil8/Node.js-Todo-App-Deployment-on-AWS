# 🚀 Node.js Todo App Deployment on AWS (ECS • EC2 • ECR • IAM • CloudWatch)

This project demonstrates an **end-to-end DevOps deployment** of a containerized **Node.js Todo Web Application** on AWS using core cloud services.  
It showcases real-world practices such as Dockerization, secure image storage, ECS orchestration, IAM-based access control, and centralized logging.

---

## 📌 Project Overview

The Node.js Todo application is containerized using Docker and deployed on AWS using **Amazon ECS (EC2 launch type)**.  
Docker images are stored securely in **Amazon ECR**, application access is controlled using **IAM**, and logs are monitored through **Amazon CloudWatch**.

This project is designed to simulate a **production-like cloud deployment workflow**.

---

## 🏗️ Architecture Workflow

1. Develop Node.js Todo application  
2. Containerize the application using Docker  
3. Push Docker image to Amazon ECR  
4. ECS cluster (EC2-backed) pulls image from ECR  
5. Container runs on EC2 instance  
6. Logs and metrics sent to CloudWatch  
7. IAM roles manage secure access between services  

---

## ⚙️ Tech Stack

- **Backend:** Node.js, Express.js  
- **Containerization:** Docker  
- **Container Registry:** Amazon ECR  
- **Orchestration:** Amazon ECS (EC2 Launch Type)  
- **Compute:** Amazon EC2  
- **Security:** AWS IAM (Roles & Policies)  
- **Monitoring & Logs:** Amazon CloudWatch

---


