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
- <img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/70de6eaa-1a2d-4007-ac16-88f3fda3af57" />

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

http://15.223.247.14:8080

---

## Docker Commands Used 

<img width="1918" height="967" alt="image" src="https://github.com/user-attachments/assets/d146cd9f-6e0c-4b1f-bece-c01c3c89778a" />

<img width="1918" height="822" alt="image" src="https://github.com/user-attachments/assets/f1bde246-5cdb-44a8-9d22-9d6695e277c8" />

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
<img width="1898" height="1078" alt="image" src="https://github.com/user-attachments/assets/7c24c787-05dc-4dbd-9f22-fa96abf2e184" />

---
## Author

Anoop Kumar

Future DevOps Engineer
