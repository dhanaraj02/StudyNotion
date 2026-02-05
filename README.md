# 📚 StudyNotion – EdTech Platform

StudyNotion is a **full-stack EdTech web application** that enables users to **create, consume, and manage online courses**.  
It supports **role-based authentication**, secure payments, and a smooth learning experience for students and instructors.

---

## 🚀 Features

### 👨‍🎓 Student
- Browse and purchase courses
- Enroll in courses using secure payments
- Watch course videos and track progress
- Manage profile and enrolled courses

### 👨‍🏫 Instructor
- Create and manage courses
- Upload video lectures and course content
- Track student enrollments
- Update or delete courses

### 🔐 Authentication & Authorization
- Role-based access (Student / Instructor / Admin)
- Secure JWT authentication
- Password hashing and validation

### 💳 Payments
- Integrated **Razorpay** payment gateway
- Secure checkout and enrollment flow

### ⚙️ Admin
- Manage users and courses
- Platform overview

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Redux Toolkit
- Tailwind CSS
- React Router
- Axios

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication

### Other Tools & Services
- Cloudinary (media storage)
- Razorpay (payments)
- bcrypt (password hashing)

---

## 📂 Project Structure
StudyNotion/
│
├── client/ # Frontend (React)
│ ├── src/
│ ├── components/
│ ├── pages/
│ ├── services/
│ └── utils/
│
├── server/ # Backend (Node + Express)
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── middlewares/
│ └── utils/
│
├── .env
├── package.json
└── README.md



