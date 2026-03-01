# 🐳 Web Server using Docker

## 📌 Project Overview
This project demonstrates how to deploy a static website using Docker containerization.  
A simple HTML webpage is served using the Nginx web server inside a Docker container.

This task was completed as part of the CodeAlpha Internship – Task 4.

---

## 🚀 Technologies Used
- Docker
- Nginx (Official Base Image)
- HTML & CSS
- Git & GitHub

---

## 📂 Project Structure

WebServer-Docker/
│── Dockerfile  
│── index.html  
│── README.md  

---

## ⚙️ Steps Performed

1. Created a static website (`index.html`)
2. Created a `Dockerfile` using Nginx as base image
3. Built Docker image
4. Ran Docker container with port mapping
5. Accessed the website using localhost
6. Managed container lifecycle
7. Pushed project to GitHub

---

## 🐳 Dockerfile Used

```dockerfile
FROM nginx:latest
COPY index.html /usr/share/nginx/html/index.html
EXPOSE 80
