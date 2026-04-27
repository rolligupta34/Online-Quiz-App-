# 🎯 Online Quiz App

A full-stack **MERN Quiz Application** built using **MongoDB, Express.js, React.js, and Node.js**.
This platform allows users to register, attend quizzes, view results, and enables admins to manage quizzes, questions, users, and analytics.

---

## 📌 Project Overview

The Online Quiz App is designed to simplify the quiz and assessment process through a modern web application. It provides secure authentication, real-time result calculation, and role-based access for users and admins.

### 👨‍🎓 User Features

* User Registration & Login
* Browse Available Quizzes
* Attempt Quizzes
* Submit Answers
* View Results & Scores
* Manage Profile

### 👨‍💼 Admin Features

* Admin Login
* Create New Quizzes
* Add / Edit / Delete Questions
* Manage Users
* View Quiz Results
* Dashboard Analytics

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* JavaScript (ES6+)
* CSS

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Authentication

* JWT (JSON Web Token)

---

## 🏗️ Project Architecture

```text
User Interface (React Frontend)
        ↓
REST API (Node.js + Express.js)
        ↓
MongoDB Database
```

The frontend communicates with backend APIs, and the backend handles business logic while storing data in MongoDB.

---

## 📂 Folder Structure

```bash
Online-Quiz-App/
│── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── App.jsx
│
│── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   └── server.js
```

---

## ⚙️ Frontend Modules

* Login / Signup
* User Dashboard
* Quiz Listing
* Quiz Attempt Page
* Result Page
* Admin Dashboard
* Quiz Management
* Analytics Panel

---

## 🔧 Backend Modules

### API Routes

* `/api/auth`
* `/api/user`
* `/api/quiz`
* `/api/result`
* `/api/admin`

### Functionalities

* User Authentication
* Quiz CRUD Operations
* Question Management
* Result Calculation
* User Management
* Analytics APIs

---

## 🗄️ Database Collections

### Users

* name
* email
* password
* role

### Quizzes

* title
* description
* questions[]

### Results

* userId
* quizId
* score
* totalQuestions

---

## 🚀 Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/rolligupta34/Online-Quiz-App-.git
cd Online-Quiz-App-
```

### 2. Setup Backend

```bash
cd backend
npm install
npm start
```

### 3. Setup Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## 🔑 Environment Variables

Create a `.env` file inside backend folder:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
```

---

## 🌟 Key Highlights

* Full MERN Stack Project
* Secure JWT Authentication
* Role-Based Access Control
* Admin Dashboard
* Quiz Management System
* Real-time Score Evaluation
* Responsive User Interface

---

## 🔮 Future Enhancements

* Timer Based Quizzes
* Leaderboard System
* Email Notifications
* Certificate Generation
* Dark Mode
* AI Generated Questions

---


