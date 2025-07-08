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

![image](https://github.com/user-attachments/assets/b3227f78-c8bc-4f43-a41e-2a0b247914f3)


🌐 Usage
Open your browser:

http://localhost:5002/ → 👋 Welcome message

http://localhost:5002/count → 🔢 Increments a visit counter in Redis


http://localhost:5000/

You should see:

![image](https://github.com/user-attachments/assets/9f11ab55-0d79-4e60-97e7-75d130298d1f)

http://localhost:5000/count

You’ll see:

![image](https://github.com/user-attachments/assets/25898c5a-b0b0-4887-8a79-0e42082b4337)
