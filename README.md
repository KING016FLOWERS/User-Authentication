# 🔐 Fullstack Authentication System

This repository contains a complete authentication system built with **Vite React.js** for the frontend, **Node.js** and **Express.js** for the backend, **MongoDB** for the database, and **Mailtrap** for email verification. The system includes signup, login, email verification, forgot/reset password functionalities, and JWT-based authentication.

## 🎯 Features

- 🔐 JWT-based authentication (Signup, Login, Logout)
- 📨 Email verification for account activation (via Mailtrap)
- 🔄 Password reset functionality
- ✔️ Protected routes for logged-in users
- 🏠 Dashboard page for authenticated users

---

## 🛠️ Tech Stack

**Frontend**:
- [Vite](https://vitejs.dev/) with React.js
- Axios for HTTP requests
- React Hook Form for form handling
- React Router for navigation

**Backend**:
- Node.js with Express.js
- MongoDB with Mongoose
- JWT for authentication
- Bcrypt for password hashing
- Nodemailer with Mailtrap for email delivery

## To Run the Code:

**Frontend**
```
cd frontend
npm run dev
```

**backend**
```
node ./backend/index.js
```

