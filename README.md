# ☁️ Docker Cloud Deployment Project

## 📌 Project Overview
This project demonstrates containerization and deployment of a portfolio website using Docker and Docker Compose.

The application is built using HTML and CSS, containerized using a Dockerfile, and configured with Docker Compose for service management.

---

## 🛠️ Tech Stack
- Docker
- Docker Compose
- Nginx
- HTML
- CSS

---

## 📂 Project Structure

docker-cloud-deployment-project/
│
├── Dockerfile
├── compose.yaml
├── index.html
├── style.css
└── README.md

---

## ⚙️ How It Works

1. Dockerfile uses Nginx as base image.
2. HTML & CSS files are copied into Nginx container.
3. Docker Compose maps port 8080 to container port 80.
4. Website runs inside container environment.

---

## 🚀 Run Locally

```bash
docker compose up --build
