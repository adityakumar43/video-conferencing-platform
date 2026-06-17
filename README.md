# 🎥 Video Conferencing Platform

A full-stack real-time video conferencing application that enables users to create and join virtual meeting rooms with secure authentication, live video/audio communication, and real-time messaging.

## 🚀 Live Demo

**Apna Video Call:** https://apnavideocallfrontend-9bn6.onrender.com/

## 📌 Project Overview

The Video Conferencing Platform is a web-based application designed to facilitate seamless online communication. Users can create meeting rooms, join existing meetings, communicate through video and audio streams, and collaborate in real time.

This project leverages modern web technologies such as WebRTC for peer-to-peer media communication and Socket.io for real-time signaling.

---

# ✨ Features

### 🔐 Authentication System

* User Registration
* User Login
* Secure JWT Authentication
* Protected Routes
* Session Management

### 🎥 Video Conferencing

* Create Meeting Rooms
* Join Existing Rooms
* Real-Time Video Streaming
* Real-Time Audio Streaming
* Multiple Participant Support

### 💬 Real-Time Chat

* Instant Messaging
* Room-Based Chat
* Live Message Updates

### 🔄 Real-Time Communication

* Socket.io Signaling Server
* Peer-to-Peer Connections
* Dynamic User Joining/Leaving Notifications

### 📱 Responsive Design

* Mobile Friendly Interface
* Tablet Compatible
* Desktop Optimized

---

# 🛠️ Tech Stack

## Frontend

* React.js
* Vite
* HTML5
* CSS3
* JavaScript (ES6+)
* Material UI

## Backend

* Node.js
* Express.js

## Database

* MongoDB

## Authentication

* JWT (JSON Web Token)

## Real-Time Communication

* Socket.io
* WebRTC

## Additional Tools

* Git
* GitHub
* Render

---

# 🏗️ System Architecture

```text
Client A
   │
   ▼
Socket.io Server
   ▲
   │
Client B

WebRTC establishes
direct peer-to-peer
audio/video connection
between clients.
```

---

# 📂 Project Structure

```text
video-conferencing-platform/
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── assets/
│   │   └── App.jsx
│   │
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── socket/
│   ├── config/
│   └── server.js
│
├── screenshots/
│
└── README.md
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/video-conferencing-platform.git

cd video-conferencing-platform
```

---

## Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

Frontend runs on:

```text
http://localhost:5173
```

---

## Backend Setup

```bash
cd backend

npm install

npm start
```

Backend runs on:

```text
http://localhost:5000
```

---

# 🔑 Environment Variables

Create a `.env` file in the backend directory.

```env
PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

CLIENT_URL=http://localhost:5173
```

---

# 🎯 Application Workflow

### Step 1

User registers and logs into the application.

### Step 2

User creates a new meeting room.

### Step 3

A unique room ID is generated.

### Step 4

Users share the room ID with participants.

### Step 5

Participants join the room.

### Step 6

Socket.io handles signaling.

### Step 7

WebRTC establishes peer-to-peer connections.

### Step 8

Video and audio streams are exchanged in real time.

### Step 9

Participants can communicate through chat messages.

---

# 🔒 Security Features

* JWT Authentication
* Password Encryption
* Protected Routes
* Secure API Access
* Environment Variable Configuration

---

# 🚀 Deployment

## Frontend Deployment (Render)

1. Push code to GitHub.
2. Create a Render Web Service.
3. Connect GitHub Repository.
4. Configure Build Command:

```bash
npm install && npm run build
```

5. Publish Directory:

```text
dist
```

6. Deploy Application.

---

## Backend Deployment

1. Create a Render Web Service.
2. Add Environment Variables.
3. Deploy Node.js Backend.

---

# 🧪 Future Enhancements

* Meeting Recording
* Virtual Backgrounds
* Hand Raise Feature
* Participant Management
* Meeting Scheduling
* Voice Activity Detection
* AI Meeting Summaries

---

# 📈 Learning Outcomes

Through this project, I gained hands-on experience in:

* Full Stack Development
* React.js Application Development
* REST API Development
* MongoDB Database Integration
* JWT Authentication
* Real-Time Communication
* Socket.io Integration
* WebRTC Implementation
* Deployment and Hosting
* Git & GitHub Workflow

