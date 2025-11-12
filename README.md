# 🐳 Flask Docker Demo — Deployed on Amazon Linux EC2

This project demonstrates how to **containerize a simple Flask application using Docker**, run it on an **Amazon Linux EC2** instance, and expose it publicly.  
It also covers **bind mounts for live code updates** and **pushing the image to Docker Hub**.

---

## 🚀 Tech Stack

- 🐍 **Python 3.10**
- 🌶️ **Flask**
- 🐳 **Docker**
- ☁️ **Amazon Linux 2 (EC2 Instance)**
- 💻 **GitHub + Docker Hub**

---

## 🧩 Step-by-Step Setup

### 1️⃣ Build Docker Image

docker build -t flask-docker-demo:v1 .

### 2️⃣ Run the Container

docker run -d -p 5000:5000 flask-docker-demo:v1

### 3️⃣ Open in your browser: http://<EC2-PUBLIC-IP>:5000

Expected output:

Hello from Flask running inside Docker on Amazon Linux EC2!

