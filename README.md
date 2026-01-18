# 📚 Student Task Management System

Ky projekt është zhvilluar si pjesë e kursit universitar dhe ka për qëllim
menaxhimin e detyrave për studentë dhe profesorë.

Aplikacioni ofron funksionalitete CRUD dhe komunikon me një REST API të ndërtuar në backend.

---

## 🚀 Funksionalitetet kryesore

- Autentikim (Login / Signup) me JWT
- Role: Student & Teacher
- Shtim i detyrave (Create)
- Lexim i detyrave (Read)
- Përditësim i detyrave (Update)
- Fshirje e detyrave (Delete)
- Ruajtje e token-it në LocalStorage
- Komunikim Frontend ↔ Backend përmes API

---

## 🧑‍💻 Teknologjitë e përdorura

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

Projekti përdor REST API për komunikim mes frontend dhe backend.

### Auth API
- `POST /api/auth/signup`
- `POST /api/auth/login`
- `GET /api/auth/me`

### Task API
- `GET /api/tasks`
- `POST /api/tasks`
- `PUT /api/tasks/:id`
- `DELETE /api/tasks/:id`

---

## 🧠 Përdorimi i TypeScript

TypeScript është përdorur për:
- Tipizimin e të dhënave (`interface User`, `Task`, `AuthResponse`)
- Siguri gjatë komunikimit me API
- Parandalimin e gabimeve gjatë zhvillimit

---

## 📂 Struktura e projektit

```bash
src/
 ├── api/
 │    ├── auth.ts
 │    └── tasks.ts
 ├── components/
 ├── pages/
 ├── App.tsx
 └── main.tsx

Si ekzekutohet projekti Frontend
npm install
npm run dev

Si ekzekutohet projekti Backend
npm install
npm start


