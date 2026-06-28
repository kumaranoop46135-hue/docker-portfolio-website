# docker-portfolio-website
A simple portfolio website containerized with Docker and deployed on an AWS EC2 Ubuntu instance using Nginx.

---
docker-portfolio-website/
│
├── README.md
├── docker-compose.yml

├── portfolio/
│   ├── Dockerfile
│   ├── index.html
│   ├── style.css
│   └── script.js

└── nginx/
    ├── Dockerfile
    └── default.conf


---
# Dockerized Portfolio Website

A simple personal portfolio website containerized using Docker and deployed on an AWS EC2 Ubuntu instance with Nginx.

---

## 📌 Project Overview

This project demonstrates how to deploy a static portfolio website using Docker.

The website is containerized and served using the official Nginx image.

The project also includes a separate Nginx Reverse Proxy configuration using Docker.

---

## 🛠 Technologies Used

- HTML5
- CSS3
- JavaScript
- Docker
- Dockerfile
- Docker Compose
- Nginx
- AWS EC2
- Ubuntu Linux

---

## 📁 Project Structure

docker-portfolio-website/

├── docker-compose.yml

├── portfolio/

│ ├── Dockerfile

│ ├── index.html

│ ├── style.css

│ └── script.js

└── nginx/

├── Dockerfile

└── default.conf

---

## 🚀 Features

- Personal Portfolio Website
- Dockerized Application
- Nginx Web Server
- Reverse Proxy Configuration
- AWS EC2 Deployment
- Easy Docker Build
- Easy Container Management

---

## ⚙️ Prerequisites

- Ubuntu Server
- Docker Installed
- AWS EC2 Instance

---

## Clone Repository

git clone https://github.com/yourusername/docker-portfolio-website.git

cd docker-portfolio-website

---

## Build Docker Image

docker build -t portfolio-app ./portfolio

---

## Run Docker Container

docker run -d \
--name portfolio-container \
-p 80:80 \
portfolio-app

---

## Verify Running Container

docker ps

---

## Open Website

http://YOUR_PUBLIC_IP

---

## Docker Commands Used

### Build Image

docker build -t portfolio-app ./portfolio

### View Images

docker images

### Run Container

docker run -d --name portfolio-container -p 80:80 portfolio-app

### Stop Container

docker stop portfolio-container

### Start Container

docker start portfolio-container

### Restart Container

docker restart portfolio-container

### Remove Container

docker rm portfolio-container

### Container Logs

docker logs portfolio-container

### List Running Containers

docker ps

### List All Containers

docker ps -a

---

## Learning Outcomes

After completing this project, I learned

- Creating Docker Images
- Writing Dockerfiles
- Running Containers
- Port Mapping
- Docker Networking Basics
- Deploying Docker Applications on AWS EC2
- Basic Nginx Configuration

---

## Future Improvements

- Add HTTPS using Let's Encrypt
- Connect Custom Domain
- GitHub Actions CI/CD
- Responsive Portfolio Design
- Contact Form

---

## Author

Anoop Kumar

Future DevOps Engineer
