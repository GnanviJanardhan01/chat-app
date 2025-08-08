# 💬 Talksy — Real-Time Chat Application

[![Python](https://img.shields.io/badge/Python-3.9+-blue)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-2.x-lightgrey)](https://flask.palletsprojects.com/)
[![Socket.IO](https://img.shields.io/badge/Socket.IO-4.x-black)](https://socket.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## 📖 Overview
**Talksy** is a lightweight, real-time chat application built with **Flask** and **Socket.IO** for the backend, and plain **HTML, CSS, and JavaScript** for the frontend.  
It allows multiple users to join a chat room and exchange messages instantly without refreshing the page.

---

## ✨ Features
- ⚡ **Real-time Messaging** — Instant communication via WebSockets
- 👥 **Multiple Users** — Join a common chat room
- 📡 **No Page Refresh** — Smooth, dynamic chat experience
- 🎨 **Clean UI** — Responsive and minimal design
- 🛠 **Easy Setup** — No database required for basic use

---

## 🛠 Tech Stack
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python, Flask
- **Real-time Communication:** Flask-SocketIO

---
## 📂 Project Structure
talksy/
│
├── static/
│ ├── css/
│ │ └── style.css # Styling for the chat UI
│ ├── js/
│ │ └── script.js # Frontend Socket.IO logic
│
├── templates/
│ └── index.html # Chat page
│
├── app.py # Flask server with Socket.IO integration
├── requirements.txt # Python dependencies
└── README.md


