# 💬 Real-Time Chat App

A full-stack real-time messaging application that enables users to communicate instantly using **Socket.IO** and **WebSocket** technology. Built with **React.js**, **Node.js**, and **Express.js**, this project delivers fast, seamless, and interactive communication with a modern user interface.

---

## ✨ Features

* 💬 Real-Time Messaging
* 👥 Multi-User Chat Support
* ⚡ Instant Message Broadcasting
* ✍️ Live Typing Indicator
* 🔌 WebSocket Communication with Socket.IO
* 🟢 User Connection & Disconnection Status
* 📱 Responsive User Interface
* 🚀 Fast & Lightweight Performance
* 🔄 Event-Based Message Handling
* 🖥️ Separate Frontend & Backend Architecture

---

## 🛠 Tech Stack

### Frontend

* React.js
* HTML
* CSS
* JavaScript
* Socket.IO Client

### Backend

* Node.js
* Express.js
* Socket.IO
* CORS

---

## 📦 Installation

### Clone Repository

```bash
git clone https://github.com/devmak26/Real-Time-Chat-App.git

cd Real-Time-Chat-App
```

---

### Install Frontend

```bash
cd frontend

npm install
```

---

### Install Backend

```bash
cd backend

npm install
```

---

## ⚙️ Environment Variables

Create a **.env** file inside the backend folder.

```env
PORT=5000

CLIENT_URL=http://localhost:5173
```

---

## ▶️ Run Application

### Start Backend

```bash
cd backend

npm run dev
```

---

### Start Frontend

```bash
cd frontend

npm run dev
```

---

## 📂 Project Structure

```text
Real-Time-Chat-App/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.jsx
│   │   └── main.jsx
│   │
│   ├── package.json
│   └── vite.config.js
│
├── backend/
│   ├── server.js
│   ├── socket/
│   ├── routes/
│   ├── package.json
│   └── .env.example
│
├── README.md

```

---

## 🔄 Application Workflow

```
User
   │
   ▼
React Frontend
   │
Socket.IO Client
   │
═══════════════════════════════
      WebSocket Connection
═══════════════════════════════
   │
Socket.IO Server
   │
Express.js
   │
Broadcast Message
   │
   ▼
Connected Users
```

---

## 🚀 Core Functionalities

* Users can join the chat instantly.
* Messages are delivered in real time without refreshing.
* Typing status is shared with connected users.
* Socket events manage communication efficiently.
* Users automatically connect and disconnect from the server.

---

## 🧪 Testing

* Real-Time Message Delivery
* Multiple Browser Testing
* Typing Indicator
* User Connection & Disconnection
* Socket Event Communication

