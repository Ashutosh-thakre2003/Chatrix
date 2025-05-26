# 💬 MERN Stack Real-Time Chat App

A full-featured real-time chat application built with the **MERN Stack** (MongoDB, Express, React, Node.js), using **Socket.IO** for instant messaging, **Zustand** for state management, and support for text, image, and more.



---

## 🚀 Features

- 🔐 JWT-based user authentication
- 💬 Real-time one-on-one messaging with Socket.IO
- 🧠 Zustand for global state management
- 🖼️ Send text, images
- 📌 Pin/unpin important messages
- ✅ Mark messages as read/unread
- 🟢 Online user tracking
- 🎥 Audio/Video call support (optional)

- ⚫ Dark mode UI

---

## 🧰 Tech Stack

### Frontend
- React
- Zustand
- Tailwind CSS
- Socket.IO Client
- Axios

### Backend
- Node.js
- Express
- MongoDB + Mongoose
- JWT
- Socket.IO Server
- Multer (for file uploads)
- CORS, Cookie-Parser, Dotenv

---

## 🛠️ Installation

### 1. Clone the repo


git clone https://github.com/your-username/mern-chat-app.git
cd mern-chat-app

setup backend :
cd backend
npm install
npm start

.env:
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret

Setup Frontend:
cd ../frontend
npm install
npm run dev


project struct.:
mern-chat-app/
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── routes/
│   │   └── socket/
│   └── uploads/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── store/ (Zustand)
│   │   └── utils/
