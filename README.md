# 🔐 Next.js, React, Symfony, MongoDB

## 🧾 Description

This is a fullstack web application built for a technical test. It allows users to register, log in, manage their profile, and perform full CRUD operations on articles.

---

## 🧰 Technologies Used

### Frontend
- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- TailwindCSS (for styling)
- Fetch API for making REST calls

### Backend
- [Symfony 6](https://symfony.com/)
- JWT Authentication (`lexik/jwt-authentication-bundle`)
- MongoDB with Doctrine ODM

### Database
- MongoDB (using official Docker image)

### DevOps / Tooling
- Docker / Docker Compose
- Environment variables in `.env`
- Jetbrains / GitHub for development

---

## 🚀 Features

### Authentication
- 🔐 JWT-based Login and Registration
- ⛔ Protected Routes using Middleware (Next.js + Symfony)

### User Account
- 👤 View and Edit Personal Information (Name, Email)

### Article Management
- 📃 List of Articles with:
  - Title, Content, Author, Publication Date
- ✏️ Create, Edit, Delete Articles
- 🔐 Users can only manage their own articles

### Pagination (✅ Implemented)
- 📄 Article list supports pagination to improve performance

---

## 🐳 How to Run (via Docker)


```bash
# Build and start the app
docker-compose up --build
```
![Demo](demo.gif)
```