# 🚀 Full-Stack Coding Interview Platform

A modern **full-stack web application** designed for conducting **technical coding interviews in real-time**.
This platform enables two users to join a secure interview room where they can **video call, write code, run test cases, and communicate live**.

---

## 🌟 Key Features

* 💻 **VSCode-like Code Editor** for solving coding problems
* 🔐 **Secure Authentication** powered by Clerk
* 🎥 **Real-time Video Interview Rooms** for interviewer and candidate
* 📊 **Interactive Dashboard** with activity insights
* 🎤 **Mic & Camera Controls**, screen sharing and recording
* 💬 **Live Chat System** during interviews
* ⚡ **Secure Code Execution Environment**
* ✅ **Automatic Code Evaluation** based on test cases
* 🎉 **Visual Feedback** (confetti on success, alerts on failure)
* 🧩 **Practice Coding Mode** for individual problem solving
* 🔒 **Room Access Control** (maximum two participants)
* 🔄 **Background Job Processing** using Inngest
* 🧰 **REST API** built with Node.js and Express
* ⚡ **Optimized Data Fetching** using TanStack Query
* 🤖 **Automated Code Review Assistance** with CodeRabbit
* 🧑‍💻 **Git & GitHub Workflow** (branches, pull requests, merges)

---

## 🛠 Tech Stack

### Frontend

* React
* Vite
* TanStack Query
* Stream Video SDK

### Backend

* Node.js
* Express.js
* MongoDB
* Inngest (background job processing)

### Authentication

* Clerk

### Deployment

* Cloud hosting (free-tier supported)

---

# ⚙️ Environment Variables

## Backend (`/backend`)

```env
PORT=3000
NODE_ENV=development

DB_URL=your_mongodb_connection_url

INNGEST_EVENT_KEY=your_inngest_event_key
INNGEST_SIGNING_KEY=your_inngest_signing_key

STREAM_API_KEY=your_stream_api_key
STREAM_API_SECRET=your_stream_api_secret

CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

CLIENT_URL=http://localhost:5173
```

---

## Frontend (`/frontend`)

```env
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key

VITE_API_URL=http://localhost:3000/api

VITE_STREAM_API_KEY=your_stream_api_key
```

---

# ▶️ Running the Project Locally

### 1️⃣ Start Backend Server

```bash
cd backend
npm install
npm run dev
```

---

### 2️⃣ Start Frontend

```bash
cd frontend
npm install
npm run dev
```

---

# 📌 Project Overview

This project demonstrates how a **modern full-stack interview platform** can be built using scalable technologies like **React, Node.js, MongoDB, and real-time video APIs**.

It simulates a real coding interview environment where candidates can **write code, run test cases, communicate via video, and receive instant feedback**.

---

# 👨‍💻 Author

Developed by **Utkarsh Johari**

---

# ⭐ Support

If you like this project, consider giving it a **star on GitHub**.
