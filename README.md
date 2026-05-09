# Docker Web UI (Minimal)

This is a minimal Flask Web UI running inside Docker.

## How to run

docker build -t webui .
docker run -p 8000:8000 webui

Then open http://localhost:8000 in your browser.

# docker-webui — Minimal Docker + Flask Web UI

This project is a **minimal Web UI running on Flask inside Docker**.  
It provides a simple structure for learning, prototyping, and extending small web applications.

---

## 🚀 Features

- Flask-based minimal web application  
- Docker containerized environment  
- Two-page UI using HTML templates  
- Bootstrap-based simple layout  
- Easy to extend for future development

---

## 📂 Directory Structure
docker-webui/
├── Dockerfile
├── app.py
├── requirements.txt
├── templates/
│   ├── index.html
│   └── info.html
└── README.md


---

## 🖥️ How to Run

### 1. Build Docker image
docker build -t webui .


### 2. Run container

docker run -p 8000:8000 webui


### 3. Access in browser

- http://localhost:8000 
- http://localhost:8000/info 

---

## 📝 Pages

### `/`
Top page with a simple Bootstrap UI.

### `/info`
Information page describing the application.

---

## 🖼️ Screenshot

![Web UI Screenshot](./Screenshot_InfoPage.png)

---

## 🛠️ Tech Stack

- Python 3.10 
- Flask 
- Bootstrap 5 
- Docker (python:3.10-slim base)

---

## 📄 License

MIT License

