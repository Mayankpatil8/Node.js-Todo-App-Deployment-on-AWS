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
- **Version Control:** Git & GitHub  

---

## 🚀 Deployment Steps (High Level)

1. Create IAM roles for ECS, EC2, and ECR  
2. Build Docker image for Node.js Todo App  
3. Push Docker image to Amazon ECR  
4. Create ECS Cluster (EC2 launch type)  
5. Configure Task Definition and Service  
6. Deploy container on EC2  
7. Monitor logs using CloudWatch  

---

## 🧪 Run Locally Using Docker

git clone https://github.com/your-username/node-todo-aws-devops.git
cd node-todo-aws-devops
docker build -t node-todo .
docker run -p 8000:8000 node-todo

--------
<img width="1919" height="1029" alt="Screenshot 2025-12-31 173812" src="https://github.com/user-attachments/assets/5c0da9a7-47e0-4a73-8aad-49bf9c879df4" />
<img width="1919" height="1030" alt="Screenshot 2025-12-31 173245" src="https://github.com/user-attachments/assets/23fd3e82-f782-4b14-af10-c323405541ca" />
<img width="1592" height="409" alt="Screenshot 2025-12-31 173216" src="https://github.com/user-attachments/assets/dab07c75-72b3-45c9-95b7-fef5f71657fe" />
<img width="1911" height="1022" alt="Screenshot 2025-12-31 173159" src="https://github.com/user-attachments/assets/884c0b8f-9d8f-41fa-ba2b-540c61bea21a" />
<img width="1919" height="1032" alt="Screenshot 2025-12-31 173124" src="https://github.com/user-attachments/assets/798ac37a-c10b-4cae-801e-91752dceb4c6" />
<img width="1919" height="1023" alt="Screenshot 2025-12-31 173109" src="https://github.com/user-attachments/assets/bbcbd3a5-30b4-4d2b-a59b-547e7a809ec9" />
<img width="1919" height="1032" alt="Screenshot 2025-12-31 173041" src="https://github.com/user-attachments/assets/e2b00be0-b9e5-404d-b6d6-26d283d979b7" />
<img width="1919" height="1030" alt="Screenshot 2025-12-31 172904" src="https://github.com/user-attachments/assets/100ed871-d9d6-4d11-afeb-42235192b299" />

