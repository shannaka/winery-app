# 🧠 Flask ML App on GKE

A lightweight machine learning web app built with Flask, originally deployed on Heroku and now running on Google Kubernetes Engine (GKE Autopilot). This app serves predictions via a simple web interface and demonstrates full-stack deployment using Docker and Kubernetes.

---

## 🚀 Live Demo

🌐 [http://34.187.148.0](http://34.187.148.0)

---

## 📦 What This App Does

- Accepts user input via a web form
- Sends data to a trained ML model
- Returns a prediction (e.g., heart disease risk)
- Runs inside a Docker container on GKE Autopilot

---

## 🛠️ How to Run Locally (with Docker)

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/flask-ml-app.git
cd flask-ml-app

# Build the Docker image
docker build -t flask-ml-app .

# Run the container
docker run -p 5000:5000 flask-ml-app

# Visit the app
http://localhost:5000
