# DPDzero DevOps Internship Assignment

This project demonstrates a simple microservices setup using **Docker Compose**, featuring:
- A **Golang service** exposing two REST endpoints
- A **Python Flask service**
- An **Nginx reverse proxy** routing traffic to each service

---

##  Project Structure
<pre> ```.
├── service_1/ # Golang application
│ ├── main.go
│ └── Dockerfile
├── service_2/ # Python Flask application
│ ├── app.py
│ ├── requirements.txt
│ └── Dockerfile
├── nginx/ # Nginx reverse proxy
│ ├── nginx.conf
│ └── Dockerfile
├── docker-compose.yml # Compose setup for all services
└── README.md
<pre> ```

---

## ⚙️ How to Run the Project

### 1. Prerequisites
Ensure you have the following installed:
- Docker
- Docker Compose

### 2. Clone & Build
```bash
git clone 
---

## ⚙️ How to Run the Project

### 1. Prerequisites
Ensure you have the following installed:
- Docker
- Docker Compose

### 2. Clone & Build
```bash
git clone https://github.com/nandakishore111/dpdzero-devops-assignment
cd SourceCodeForDevopsAssignment
docker compose up --build
All three services will be up and running in isolated containers.

