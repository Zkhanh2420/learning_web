<div align="center">

# 🎓 Learnow

### A Free Full-Stack Online Learning Platform

[![React](https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-Express-339933?style=flat-square&logo=node.js)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-Mongoose-47A248?style=flat-square&logo=mongodb)](https://mongodb.com/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-06B6D4?style=flat-square&logo=tailwindcss)](https://tailwindcss.com/)
[![Vite](https://img.shields.io/badge/Vite-Build-646CFF?style=flat-square&logo=vite)](https://vitejs.dev/)

*Empowering learners. Enabling instructors. Built for scale.*

</div>

---

## 📖 Overview

**Learnow** is a production-ready MERN stack web application that simulates a real-world EdTech platform. It enables students to discover and enroll in free courses, instructors to build and publish structured content, and administrators to govern the entire platform — all powered by a secure, role-based architecture.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | React 18, Vite, Tailwind CSS, React Router, Axios |
| **Backend** | Node.js, Express, TypeScript |
| **Database** | MongoDB, Mongoose |
| **Auth** | JWT (JSON Web Tokens) |
| **Media Storage** | Cloudinary |
| **State Management** | Zustand / Redux |

---

## ✨ Features

### 👤 Student
- Register, log in, and manage profile
- Browse and search available courses
- Enroll and watch video lectures
- Track learning progress per course

### 👨‍🏫 Instructor
- Create and publish courses with structured sections & lessons
- Upload lecture videos via Cloudinary
- Edit course details and manage content
- View list of enrolled students

### 🛡️ Admin
- Manage all users and assign roles (Admin / Instructor / Student)
- Review, approve, or remove courses
- Full control over platform content and permissions

---

## 🚀 Getting Started

### Prerequisites

- Node.js >= 18
- MongoDB (local or Atlas)
- Cloudinary account

### 1. Clone the Repository

```bash
git clone https://github.com/socodo/learnow.git
cd learnow
```

### 2. Configure Environment Variables

Create a `.env` file inside the `server/` directory:

```env
PORT=8080
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

### 3. Start the Backend

```bash
cd server
npm install
npm run dev
# Server running at http://localhost:8080
```

### 4. Start the Frontend

```bash
cd client
npm install
npm run dev
# App running at http://localhost:3000
```

---

## 🔑 Demo Accounts

| Role | Email | Password |
|---|---|---|
| 👤 Student | dat.nguyendat@gmail.com | Tandat16122005 |
| 🛡️ Admin | fluoxetines73@gmail.com | 4dm1nF1u0 |

---

## 🗂️ Project Structure

```
learnow/
├── client/               # React frontend (Vite)
│   └── src/
│       ├── features/     # Feature-based modules (auth, courses, admin…)
│       ├── service/      # Axios API services
│       ├── shared/       # Layouts, shared components, contexts
│       └── store/        # Global state management
└── server/               # Express backend (TypeScript)
    └── src/
        ├── controller/   # Route handler logic
        ├── models/       # Mongoose schemas
        ├── router/       # API route definitions
        ├── middlewares/  # Auth, upload, validation
        └── validations/  # Request schema validation
```

---

## 💡 Key Learnings

- Designing scalable RESTful APIs with Express.js and TypeScript
- Implementing secure authentication and role-based authorization using JWT
- Managing client-side state with Zustand/Redux
- Handling cloud media uploads with Cloudinary
- Structuring a maintainable full-stack MERN application

---

## 📬 Contact

Have questions or feedback? Reach out:

📧 **anh.trannguyen@hcmut.edu.vn**
