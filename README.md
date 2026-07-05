# 📚 Online Course Management System (OCMS)

A session-based **Online Course Management System** built using **Node.js, Express.js, MongoDB, Mongoose, EJS, Bootstrap, and MVC Architecture**. The application allows users to register, log in securely, and perform CRUD operations on course records. Session management ensures that only authenticated users can access protected features.

---

## 🎯 Objective

Develop a secure web application that implements:

- User Registration
- User Login & Logout
- Session-Based Authentication
- Course Management (CRUD)
- MVC Architecture
- MongoDB Integration

---

## 🚀 Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- EJS
- Bootstrap 5
- Express Session
- HTML5
- CSS3
- JavaScript

---

## ✨ Features

### User Authentication

- User Registration
- Secure Login
- Session-Based Authentication
- Logout Functionality

### Course Management

- Add New Course
- View All Courses
- Update Course Details
- Delete Course

### Session Management

Only authenticated users can access:

- Dashboard
- Add Course
- View Courses
- Update Course
- Delete Course
- Logout

Unauthenticated users are automatically redirected to the Login page.

### MVC Architecture

Project follows the MVC design pattern.

```
OCMS/
│
├── controllers/
├── models/
├── routes/
├── views/
├── public/
├── screenshots/
├── app.js
├── package.json
└── README.md
```

---

## 📂 Database Schema

### User

| Field | Type |
|--------|------|
| Full Name | String |
| Email | String |
| Password | String |

### Course

| Field | Type |
|--------|------|
| Course Name | String |
| Trainer Name | String |
| Duration | String |
| Fees | Number |

---

## 📸 Screenshots

Store screenshots inside the **Screenshots** folder.

Required screenshots:

- User Registration
- User Login
- Dashboard
- Insert Course
- Display Courses
- Update Course
- Delete Course (Before)
- Delete Course (After)
- MongoDB Collections
- GitHub Repository Structure

Example:

```
Screenshots/
├── registration.png
├── login.png
├── dashboard.png
├── add-course.png
├── display-course.png
├── update-course.png
├── delete-before.png
├── delete-after.png
├── mongodb.png
└── repository.png
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/ashh790/Online-course-management.git
```

### Move into Project

```bash
cd Online-course-management
```

### Install Dependencies

```bash
npm install
```

---

## 🛠 Configure MongoDB

Start MongoDB locally.

Example connection:

```javascript
mongodb://127.0.0.1:27017/ocms
```

Update the connection string in your project if required.

---

## ▶️ Run Project

Start the server:

```bash
npm start
```

or

```bash
nodemon app.js
```

Open:

```
http://localhost:3000
```

---

## 📁 Project Structure

```
OCMS
│
├── controllers
│   ├── authController.js
│   └── courseController.js
│
├── models
│   ├── User.js
│   └── Course.js
│
├── routes
│   ├── authRoutes.js
│   └── courseRoutes.js
│
├── views
│
├── public
│
├── Screenshots
│
├── app.js
├── package.json
└── README.md
```

---

## ✅ Functional Modules

- User Registration
- User Login
- User Logout
- Session Authentication
- Insert Course
- Display Courses
- Update Course
- Delete Course
- Protected Routes
- MongoDB Integration
- MVC Architecture

---

## 🔒 Session Protection

Protected routes:

- Dashboard
- Add Course
- Display Courses
- Update Course
- Delete Course
- Logout

Users attempting to access these routes without authentication are redirected to the Login page.

---

## 👨‍💻 Author

**Ashraf Dalal**

GitHub: https://github.com/ashh790

Repository:

https://github.com/ashh790/Online-course-management

---

## 📜 License

This project is developed for educational purposes as part of a Node.js, Express.js, MongoDB, and MVC Architecture assignment.