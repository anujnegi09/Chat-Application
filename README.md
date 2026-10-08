# 💬 Chat Application

A real-time chat application built to practice and demonstrate **full-stack web development**, including user authentication, messaging, API development, database management, and real-time communication.

## 🚀 Overview

This project is a full-stack chat application where users can communicate with each other through a simple and modern chat interface.

The project is being developed as a practical learning project to improve my skills in **React.js, Node.js, Express.js, MongoDB, REST APIs, authentication, and real-time communication**.

## ✨ Features

* 👤 User registration and login
* 🔐 User authentication
* 💬 One-to-one messaging
* ⚡ Real-time message communication
* 🟢 Online/offline user status
* 📱 Responsive chat interface
* 🗃️ Persistent chat and message data
* 🔎 User search
* 🔒 Protected API routes

> More features will be added as the project develops.

## 🛠️ Tech Stack

### Frontend

* React.js
* JavaScript
* HTML5
* CSS3
* Redux Toolkit
* Axios

### Backend

* Node.js
* Express.js
* REST API
* Socket.IO

### Database

* MongoDB
* Mongoose

### Authentication

* JWT
* HTTP-only Cookies

### Tools & Services

* Git & GitHub
* Postman
* VS Code

## 📁 Project Structure

```text
Chat-Application/
│
├── client/                 # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── redux/
│   │   ├── services/
│   │   └── App.jsx
│   └── package.json
│
├── server/                 # Node.js + Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── socket/
│   ├── config/
│   └── server.js
│
├── .gitignore
├── README.md
└── package.json
```

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/anujnegi09/Chat-Application.git
```

### 2. Navigate to the project

```bash
cd Chat-Application
```

### 3. Install dependencies

For the backend:

```bash
cd server
npm install
```

For the frontend:

```bash
cd ../client
npm install
```

### 4. Configure environment variables

Create a `.env` file inside the `server` directory.

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLIENT_URL=http://localhost:5173
```

### 5. Start the backend

```bash
cd server
npm run dev
```

### 6. Start the frontend

Open another terminal:

```bash
cd client
npm run dev
```

The application will normally be available at:

```text
http://localhost:5173
```

## 🔄 How It Works

```text
User
  │
  ▼
React Frontend
  │
  ├── REST API ──────► Express.js Server
  │                         │
  │                         ▼
  │                      MongoDB
  │
  └── Socket.IO ─────► Real-time Communication
```

The frontend communicates with the backend through REST APIs for operations such as authentication and retrieving data.

**Socket.IO** is used for real-time communication between connected users.

## 🎯 Learning Goals

This project is mainly focused on improving practical knowledge of:

* Building a full-stack application
* Creating REST APIs with Express.js
* Working with MongoDB and Mongoose
* Implementing authentication
* Managing frontend state with Redux Toolkit
* Implementing real-time communication with Socket.IO
* Connecting frontend and backend applications
* Using Git and GitHub for version control
* Deploying full-stack applications

## 🔮 Future Improvements

* 👥 Group chats
* 📎 File and image sharing
* 🎤 Voice messages
* 🔔 Notifications
* ✏️ Edit and delete messages
* 🟢 Better online/offline presence
* 👀 Message read receipts
* 🌙 Dark mode
* 📱 Improved mobile experience

## 👨‍💻 Author

**Anuj Negi**

BCA Graduate | Currently pursuing MCA
Full-Stack Developer | React.js | Node.js | Express.js | MongoDB

* GitHub: [Anuj Negi](https://github.com/anujnegi09)
* LinkedIn: [Anuj Negi](https://linkedin.com/in/anuj-negi-65442b349/)

## ⭐ Support

If you find this project useful or interesting, consider giving the repository a ⭐ on GitHub.
