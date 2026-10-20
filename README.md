# 📚 Student Task Management System

This project was developed as part of a university course and is designed to manage tasks for students and teachers.

The application provides CRUD functionality and communicates with a REST API built on the backend.

---

## 🚀 Key Features

- Authentication (Login / Signup) using JWT
- User roles: Student & Teacher
- Create tasks
- Read and view tasks
- Update tasks
- Delete tasks
- Store authentication tokens in LocalStorage
- Frontend ↔ Backend communication through an API

---

## 🧑‍💻 Technologies Used

### Frontend
- React
- TypeScript
- Axios
- React Hooks

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication

---

## 🔌 REST API

The project uses a REST API to enable communication between the frontend and backend.

### Authentication API
- `POST /api/auth/signup`
- `POST /api/auth/login`
- `GET /api/auth/me`

### Task API
- `GET /api/tasks`
- `POST /api/tasks`
- `PUT /api/tasks/:id`
- `DELETE /api/tasks/:id`

---

## 🧠 Use of TypeScript

TypeScript is used for:

- Type definitions for data structures (`interface User`, `Task`, `AuthResponse`)
- Type safety when communicating with the API
- Reducing errors during development

---

## 📂 Project Structure

```bash
src/
 ├── api/
 │    ├── auth.ts
 │    └── tasks.ts
 ├── components/
 ├── pages/
 ├── App.tsx
 └── main.tsx
```

---

## ⚙️ How to Run the Project

### Frontend

```bash
npm install
npm run dev
```

### Backend

```bash
npm install
npm start
```
