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
8. <img width="1621" height="735" alt="image" src="https://github.com/user-attachments/assets/0bb81c8d-9b85-4f38-8263-8ba4a92fda82" />


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
<img width="1919" height="1030" alt="Screenshot 2025-12-31 172904" src="https://github.com/user-attachments/assets/401964da-d56a-4b11-be37-37069622f26e" />
--------
<img width="1919" height="1032" alt="Screenshot 2025-12-31 173041" src="https://github.com/user-attachments/assets/5f19411d-08db-4908-8924-4099aceb72ba" />
--------
<img width="1919" height="1023" alt="Screenshot 2025-12-31 173109" src="https://github.com/user-attachments/assets/b01ce73f-ffbb-4538-b0fe-a9a728d1dbad" />
-------
<img width="1919" height="1032" alt="Screenshot 2025-12-31 173124" src="https://github.com/user-attachments/assets/0620bb7c-eb01-4cc5-ad9d-aa0ab67beca4" />
-------
<img width="1911" height="1022" alt="Screenshot 2025-12-31 173159" src="https://github.com/user-attachments/assets/ea1644fc-4bb8-4960-902a-c66e3a095518" />
-------
<img width="1592" height="409" alt="Screenshot 2025-12-31 173216" src="https://github.com/user-attachments/assets/e9a7ca21-bed2-43d1-a520-d5f8caf279f7" />
-------
<img width="1919" height="1030" alt="Screenshot 2025-12-31 173245" src="https://github.com/user-attachments/assets/f3c1d360-5a37-4698-90c0-cbb2b65437a7" />
--------
<img width="1919" height="1029" alt="Screenshot 2025-12-31 173812" src="https://github.com/user-attachments/assets/ae1a5c67-342e-454f-be72-e5d9a26ef65f" />

