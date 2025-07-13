# 🎓 Marstan – Admin Panel for Gamified Educational App

This is the **admin dashboard** for **Marstan**, a gamified educational platform. Built with the **MERN stack**, this web-based panel allows authorized administrators to create and manage educational content such as **forms**, **questions/answers**, and **images** — all fully synced with the mobile learning app.

The backend supports **JWT-based authentication with refresh tokens** and enforces **role-based access control (RBAC)** to secure content management endpoints.

---
[Download on Google Play](https://play.google.com/store/apps/details?id=education.ayata.marstan&hl=fr)


## 🚀 Features

- 🧩 **Admin-Only Interface**  
  Designed exclusively for trusted admins to manage content — no teacher/student views.

- 📄 **Manage Forms, Questions & Answers**  
  Create, edit, and delete learning activities that power the mobile game logic.

- 🖼️ **Attach Images to Content**  
  Optional image support for visual questions and interactive elements.

- 🔐 **JWT Authentication with Refresh Tokens**  
  Access tokens are short-lived for security. Refresh tokens are securely stored and rotated for persistent sessions.

- 🛡️ **Role-Based Access Control (RBAC)**  
  Protects all admin routes from unauthorized access using role-specific middleware.

- 🔁 **Mobile App Integration**  
  The backend serves live educational content to a separate gamified mobile client.

- 🧼 **Clean Code Architecture**  
  Follows modular design principles, controller/service separation, and consistent REST API patterns.

---

## 🛠 Tech Stack

| Layer       | Technology            |
| ----------- | --------------------- |
| Frontend    | React.js, Axios       |
| Backend     | Node.js, Express      |
| Database    | MongoDB (Mongoose)    |
| Auth        | JWT + Refresh Tokens  |
| Access Ctrl | Role-Based Middleware |

---
