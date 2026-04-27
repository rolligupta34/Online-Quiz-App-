# 🎯 MERN Quiz Application

A full-stack **Online Quiz Management System** built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**.
This platform allows users to register, attempt quizzes, view results, and enables admins to manage quizzes, questions, users, and analytics.

---

## 📌 Project Overview

The MERN Quiz Application is designed to digitize the quiz/test process with real-time scoring and role-based access.

### 👨‍🎓 User Side:

* Register / Login
* View available quizzes
* Attempt quizzes
* Submit answers
* View results & scores

### 👨‍💼 Admin Side:

* Secure admin login
* Create quizzes
* Add / Edit / Delete questions
* Manage users
* Track quiz performance
* View analytics dashboard

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* JavaScript (ES6+)
* CSS / Tailwind CSS (if used)
* Axios / Fetch API

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Authentication & Security

* JWT (JSON Web Token)
* Protected Routes
* Role-Based Access Control

---

## 🏗️ Project Architecture

Client (React Frontend)
⬇
REST API (Express Backend)
⬇
MongoDB Database

The frontend communicates with backend APIs, and the backend processes business logic while storing/retrieving data from MongoDB.

---

## 📂 Folder Structure

```bash
project-root/
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

### Routes

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

### 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

### 2️⃣ Setup Backend

```bash
cd backend
npm install
npm start
```

### 3️⃣ Setup Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## 🔑 Environment Variables

Create a `.env` file inside backend:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
```

---

## 📸 Screenshots

* Home Page
* 
* User Login
* Quiz Dashboard
* Quiz Attempt
* Result Page
* Admin Dashboard
* Add Quiz Page
* Analytics Page

(Add screenshots here)

---



## 🔮 Future Enhancements

* Timer-based quizzes
* Leaderboard system
* Email notifications
* Certificate generation
* Dark mode UI
* AI-generated questions

---

