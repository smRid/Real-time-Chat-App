# 💬 Realtime Chat App

A full-stack **Realtime Chat Application** built with the **MERN stack** (MongoDB, Express.js, React.js, Node.js) and **Socket.io** for seamless, real-time messaging. The app features user authentication, real-time communication, and a fully responsive UI optimized for both desktop and mobile devices.

---


## 🔗 Preview

![Dashboard Preview](frontend/public/preview1.png) 
--
🌍 Live Demo - https://chat-app-rt-w3n8.onrender.com/

---

## 🚀 Features

- 🔒 JWT-based user authentication  
- 🧠 Global state management using Zustand  
- 💬 Real-time chat updates via Socket.io  
- 🖼️ Cloudinary integration for profile image uploads  
- ☁️ Responsive and mobile-friendly UI with DaisyUI  
- 🔔 Instant notifications with react-hot-toast  
- 🛠️ RESTful API with Express & MongoDB  
- 🔄 Persistent login using cookies  
- 🌐 Modern routing with React Router DOM v7  

---

## 🖥️ Tech Stack

### Frontend

- React.js `v19`
- Zustand for state management
- DaisyUI + Tailwind CSS for UI
- React Router DOM `v7`
- Axios for API communication
- Socket.io-client for real-time events
- Lucide-react for icons
- React-hot-toast for notifications

### Backend

- Node.js & Express.js `v5`
- MongoDB with Mongoose
- Socket.io `v4.8.1`
- JWT for authentication
- Bcrypt.js for password hashing
- Cloudinary for media uploads
- Cookie-parser for session handling
- CORS and dotenv for configuration

---




## ⚙️ Installation

###  Clone the Repository

```bash
git clone https://github.com/smRid/Real-time-Chat-App.git
```

# Setup .env file
```bash
MONGODB_URI=...
PORT=5001
JWT_SECRET=...

CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...

NODE_ENV=development
```

### Build the app

```shell
npm run build
```

### Start the app

```shell
npm run start
```
