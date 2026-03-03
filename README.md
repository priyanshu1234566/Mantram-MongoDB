# 🚀 Mantram MongoDB Web Application

🔗 **Live Demo:** https://mantram-mongo-db.vercel.app/

A full-stack web application built using **React + Vite** for the frontend and **Node.js, Express, and MongoDB** for the backend.  
This project demonstrates CRUD operations, REST API integration, and modern development practices.

---

## 📌 Tech Stack

### 🖥 Frontend
- React.js
- Vite
- Axios
- Tailwind CSS (if used)
- ESLint

### 🌐 Backend
- Node.js
- Express.js
- MongoDB
- dotenv
- body-parser / express.json()

---

## ✨ Features

- ✅ Create Data
- ✅ Read Data
- ✅ Update Data
- ✅ Delete Data
- ⚡ Fast Development with Vite (HMR)
- 🔐 Environment Variable Support
- 🌍 REST API Integration

---

## 📂 Project Structure

```
Mantram-MongoDB/
│
├── client/              # React Frontend
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/              # Express Backend
│   ├── index.js
│   ├── routes/
│   ├── models/
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

---

### 2️⃣ Backend Setup

```bash
cd server
npm install
```

Create a `.env` file inside the server folder:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

Start Backend Server:

```bash
npm start
```

---

### 3️⃣ Frontend Setup

```bash
cd client
npm install
npm run dev
```

Frontend will run on:

```
http://localhost:5173
```

---

## 🚀 Available Scripts

### Frontend
- `npm run dev` → Start development server
- `npm run build` → Production build
- `npm run preview` → Preview production build

### Backend
- `npm start` → Start server
- `npm run dev` → Start server with nodemon (if installed)

---

## 🌍 Deployment

- **Frontend:** Deployed on Vercel  
- **Backend:** Can be deployed on Render / Railway / VPS  
- **Database:** MongoDB Atlas

---

## 📖 About Vite + React

This project uses Vite for faster builds and Hot Module Replacement (HMR).

Available official plugins:

- `@vitejs/plugin-react` (Babel based)
- `@vitejs/plugin-react-swc` (SWC based)

---

## 🧠 Future Improvements

- 🔐 Add Authentication (JWT)
- 📊 Add Dashboard UI
- 🌈 Improve UI/UX
- 📦 Add TypeScript Support
- 🧪 Add Testing (Jest / Vitest)

---

## 👨‍💻 Author

Developed by **Priyanshu Kumar**

If you like this project, don’t forget to ⭐ the repository!

---
