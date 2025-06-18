# 🍔 Food App

A full-stack Food Delivery Admin Panel built with **React** (frontend) and **Node.js** (backend), featuring dynamic food management, order tracking, and a user-friendly interface.

---

## 📁 Project Structure
```
Food-App-main/
├── admin/ # Frontend (React + Vite)
│ ├── public/
│ ├── src/
│ │ ├── assets/ # Images and static assets
│ │ ├── components/ # Reusable UI components
│ │ │ ├── Navbar/
│ │ │ └── Sidebar/
│ │ ├── pages/ # Feature-based page components
│ │ │ ├── Add/
│ │ │ ├── List/
│ │ │ └── Orders/
│ │ ├── App.jsx
│ │ ├── main.jsx
│ │ └── index.css
│ ├── index.html
│ ├── package.json
│ └── vite.config.js
├── backend/ # Backend (Node.js + Express + MongoDB)
│ ├── config/
│ │ ├── db.js # MongoDB connection
│ │ └── multerConfig.js # File upload config
│ ├── index.js # Server entry point
│ ├── package.json
│ └── vercel.json

```

## 🚀 Features

- Admin panel to:
  - Add new food items
  - View and manage food list
  - View and track orders
- File/image upload support using **Multer**
- RESTful API backend using **Express.js**
- MongoDB integration for data storage

---

## 🛠️ Technologies Used

### Frontend:
- React
- Vite
- CSS Modules

### Backend:
- Node.js
- Express.js
- MongoDB (Mongoose)
- Multer

---

## 🧑‍💻 Getting Started

### Backend Setup

```bash
cd backend
npm install
node index.js
```

### Frontend Setup
```bash
cd admin
npm install
npm run dev
```
## 📦 Deployment
Designed to deploy easily on Vercel (with vercel.json included).

## 📜 License
This project is licensed under the MIT License.
