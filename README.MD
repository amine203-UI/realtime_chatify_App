<h1 align="center">💬 Full-Stack Chat Application</h1>

<p align="center">
  <img src="/frontend/public/screenshot-for-readme.png" alt="Chat App Demo" width="700">
</p>


---

## 🚀 Overview

A modern, full-featured **chat application** built using the **MERN stack (MongoDB, Express.js, React, Node.js)** with **real-time messaging**, **JWT authentication**, and **email notifications**.  
This project demonstrates full-stack development, deployment readiness, and professional Git/GitHub workflows.

---

## ✨ Key Features

- 🔐 **Custom JWT Authentication** (no third-party auth)
- ⚡ **Real-Time Messaging** powered by Socket.io
- 🟢 **Online/Offline Presence Indicators**
- 🔔 **Notification & Typing Sounds** (toggleable)
- 📨 **Automated Welcome Emails** using Resend
- 🗂️ **Image Uploads** integrated with Cloudinary
- 🧰 **RESTful API** with Node.js & Express
- 🧱 **MongoDB** for data persistence
- 🚦 **API Rate Limiting** via Arcjet
- 🎨 **Responsive UI** built with React, Tailwind CSS & DaisyUI
- 🧠 **Global State Management** with Zustand
- 🧑‍💻 **Version Control Workflow** using Git & GitHub (branches, PRs, merges)
- ☁️ **Easy Deployment** (optimized for free-tier hosting such as Sevalla)

---

## ⚙️ Environment Variables Setup

Create a `.env` file inside the **`/backend`** directory with the following configuration:

```bash
PORT=3000
MONGO_URI=your_mongo_uri_here
NODE_ENV=development

JWT_SECRET=your_jwt_secret

RESEND_API_KEY=your_resend_api_key
EMAIL_FROM=your_email_from_address
EMAIL_FROM_NAME=your_email_from_name

CLIENT_URL=http://localhost:5173

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

ARCJET_KEY=your_arcjet_key
ARCJET_ENV=development
```



🧩 Installation & Setup

1️⃣ Backend Setup
```bash
cd backend
npm install
npm run dev
```
2️⃣ Frontend Setup
```bash
cd frontend
npm install
npm run dev
```






