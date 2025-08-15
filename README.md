# 📝 Post Manager App (MERN)

A full-stack MERN CRUD application to manage blog posts. Users can create, read, update, and delete posts with a clean and responsive interface. Built to showcase full-stack development skills from backend API creation to frontend UI design.

---

## 🚀 Features
- Create, edit, delete, and view blog posts
- Responsive and mobile-friendly UI
- RESTful API with Express.js
- MongoDB integration using Mongoose
- Axios for frontend-backend communication
- Deployed on Render (Backend) & Vercel (Frontend)

---

## 🛠 Tech Stack
**Frontend:** React.js, Axios, Tailwind CSS  
**Backend:** Node.js, Express.js  
**Database:** MongoDB (Mongoose)  
**Hosting:** Render (Backend), Vercel (Frontend)

---

## 📂 Project Structure
post-manager-app/
│
├── backend/ # Backend (Node.js + Express)
│ ├── controllers/ # Route controllers
│ ├── models/ # Mongoose schemas
│ ├── routes/ # API route definitions
│ ├── .env # Environment variables
│ ├── server.js # Entry point for backend
│ └── package.json # Backend dependencies
│
├── frontend/ # Frontend (React.js)
│ ├── public/ # Public assets
│ ├── src/
│ │ ├── Pages/ # Page components
│ │ │ ├── Homepage.js
│ │ │ ├── Homepage.css
│ │ │ ├── PostManager.js
│ │ │ └── PostManager.css
│ │ ├── App.js
│ │ ├── index.js
│ │ ├── index.css
│ │ └── setupTests.js
│ ├── package.json # Frontend dependencies
│
├── README.md # Project documentation
└── .gitignore
