# 🚀 Flask + Redis Multi-Container App (Dockerized)

This project is a simple multi-container application using **Python Flask** and **Redis**, orchestrated with **Docker Compose**. It demonstrates how to use Redis as a key-value store to track visit counts in a web app.

---

## 📌 Features

- 🔧 Simple Flask web application with two routes:
  - `/` – Displays a welcome message
  - `/count` – Increments and displays a visit count stored in Redis
- 🐳 Dockerized using separate containers for the app and database
- ⚙️ Managed with Docker Compose
- 💾 Redis persistence with volumes
- 🌐 Environment-based Redis config
- 📈 Optional: Scale the web app to multiple instances

---

## 📁 Project Structure

flask-redis-app/
├── app/
│ ├── app.py
│ ├── requirements.txt
│ └── Dockerfile
├── docker-compose.yml
└── README.md

🌐 Usage
Open your browser:

http://localhost:5002/ → 👋 Welcome message

http://localhost:5002/count → 🔢 Increments a visit counter in Redis


