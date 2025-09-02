# 🐍 Flask Snake Game (Dockerized)

A simple **Snake Game** built with **Flask (Python)** and rendered using **HTML, CSS, and JavaScript (Canvas API)**.  
This repository is primarily designed to demonstrate **containerization** and **deployment** practices using Docker.  

---

## 🚀 Features
- Web-based classic Snake Game
- Lightweight Python Flask backend
- Simple HTML/CSS/JS frontend
- Fully containerized using **Docker**
- Easy to run locally or deploy on cloud/Kubernetes

---

---

## 🐳 Docker Setup

### 1️⃣ Build Docker Image
```bash
docker build -t flask-snake-game .

##2️⃣ Run Container
docker run -d -p 5000:5000 flask-snake-game
