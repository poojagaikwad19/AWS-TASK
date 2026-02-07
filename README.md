# AWS DevOps Intern Assignment – Full Stack App Deployment

## 👋 Overview

This project is a simple full-stack web application created as part of the AWS & DevOps Intern assignment.

The application includes:
- Frontend (HTML, CSS, JavaScript)
- Backend (Node.js + Express)
- Database (MongoDB)
- Docker for containerization
- Deployment on AWS EC2

The main goal is to show the complete DevOps flow:
Build the app → Dockerize it → Run locally → Deploy on AWS → Access via public IP → Troubleshoot issues.

---

## 🛠️ Tech Stack

- Frontend: HTML, CSS, JavaScript  
- Backend: Node.js, Express  
- Database: MongoDB  
- Containerization: Docker, Docker Compose  
- Cloud: AWS EC2 (t2.micro / t3.micro)  
- OS: Ubuntu (on EC2)

---

## 📦 Features

- User management (Add, List, Delete users)
- Registration page
- Login page
- Backend API with MongoDB
- Frontend served by backend
- Health check endpoint (`/health`)
- Dockerized setup (backend + database)
- Containers auto-restart using Docker

---

## 🗂️ Project Structure

aws-devops-assignment/
├─ backend/
│ ├─ Dockerfile
│ ├─ index.js
│ ├─ package.json
│ └─ frontend/
│ ├─ index.html
│ ├─ register.html
│ └─ login.html
└─ docker-compose.yml


# Also there are some blockers I faced, so I have attached them below:

![Cannot GET /](https://raw.githubusercontent.com/poojagaikwad19/Aws-Devops-Assigment/master/Screenshot/cannot-get-root.png.jpeg)

![Docker Copy Error](https://raw.githubusercontent.com/poojagaikwad19/Aws-Devops-Assigment/master/Screenshot/docker-copy-error.png.jpeg)

![Dockerfile Not Found](https://raw.githubusercontent.com/poojagaikwad19/Aws-Devops-Assigment/master/Screenshot/dockerfile-not-found.png.jpeg)

![Failed Fetch Users](https://raw.githubusercontent.com/poojagaikwad19/Aws-Devops-Assigment/master/Screenshot/failed-fetch-users.png.jpeg)

![Frontend Not Found](https://raw.githubusercontent.com/poojagaikwad19/Aws-Devops-Assigment/master/Screenshot/frontend-not-found.png.jpeg)

![Frontend Path Error](https://raw.githubusercontent.com/poojagaikwad19/Aws-Devops-Assigment/master/Screenshot/frontend-path-error.png.jpeg)

![Mongo Connection Error](https://raw.githubusercontent.com/poojagaikwad19/Aws-Devops-Assigment/master/Screenshot/mongo-connection-error.png.jpeg)

![Simple Frontend Working](https://raw.githubusercontent.com/poojagaikwad19/Aws-Devops-Assigment/master/Screenshot/simple-frontend-working.png.jpeg)ection-error.png.jpeg)

![Simple Frontend Working](https://raw.githubusercontent.com/poojagaikwad19/Aws-Devops-Assigment/main/screenshots/simple-frontend-working.png.jpeg)




