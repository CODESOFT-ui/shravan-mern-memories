# 🌟 MERN Memories – Full Stack Social Media Application

## 📌 Overview

**MERN Memories** is a full-stack web application where users can create, view, update, and delete posts (memories).
The project demonstrates the complete **MERN stack architecture** by combining a React frontend, Node.js backend, Express API, and MongoDB database.

Users can share personal memories with text, tags, and images. The application stores and retrieves data dynamically from a cloud database.

This project was built to understand how a **real-world full stack application works** and how the frontend, backend, and database communicate together.

---

## 🛠 Tech Stack

### 🎨 Frontend

* React
* Redux
* Axios
* Material UI

### ⚙️ Backend

* Node.js
* Express.js
* REST API

### 🗄 Database

* MongoDB Atlas (Cloud Database)

### 🧰 Development Tools

* Git & GitHub
* VS Code
* npm

---

## 🏗 Architecture

React (Frontend UI)
⬇
Redux / Axios (API Requests)
⬇
Express Server (Backend API)
⬇
MongoDB Atlas (Database)

---

## ✨ Features

### 📝 Create Memories

Users can create posts including:

* Creator name
* Title
* Message
* Tags
* Image upload

### 📖 View Posts

All memories are displayed dynamically from the MongoDB database.

### ✏️ Edit Posts

Users can update existing memories.

### 🗑 Delete Posts

Users can remove posts from the database.

### ❤️ Like System

Users can like posts to show appreciation.

### 🖼 Image Upload

Posts support image uploads encoded and stored along with the memory.

---

## 📂 Folder Structure

project_mern_memories
│
├── client
│ └── src
│ ├── actions
│ ├── components
│ ├── reducers
│ ├── api
│ └── App.js
│
├── server
│ ├── controllers
│ ├── models
│ ├── routes
│ └── index.js
│
└── README.md

## ⚙️ How It Works

1️⃣ User fills the memory form in the React frontend.
2️⃣ React sends the data to the backend using Axios.
3️⃣ Express receives the request through REST API routes.
4️⃣ The server stores the post in MongoDB Atlas.
5️⃣ MongoDB returns the stored data.
6️⃣ React updates the UI and displays the post.

---

## 🚀 Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/CODESOFT-ui/shravan-mern-memories.git
cd shravan-mern-memories
```

---

### 2️⃣ Install Backend Dependencies

```
cd server
npm install
```

---

### 3️⃣ Install Frontend Dependencies

```
cd client
npm install
```

---

### 4️⃣ Configure Database

Create a MongoDB Atlas cluster and obtain the connection string.

Update the MongoDB connection inside:

```
server/index.js
```

Example:

```
const CONNECTION_URL = "mongodb+srv://username:password@cluster.mongodb.net/memories"
```

---

### 5️⃣ Run Backend Server

```
cd server
npm start
```

Server runs on:

```
http://localhost:5000
```

---

### 6️⃣ Run Frontend

```
cd client
npm start
```

Frontend runs on:

```
http://localhost:3000
```

---

## 📸 Screenshots

Home Page
Create Memory Form
Posts Feed

(Add screenshots later for better documentation)

---

## 🔮 Future Improvements

🔐 Authentication system (Login / Signup)
💬 Comments feature
👤 User profiles
📄 Pagination
🔍 Search functionality
☁️ Cloud deployment

---

## 🎯 Learning Outcomes

This project demonstrates:

* MERN stack architecture
* REST API development
* MongoDB database integration
* React state management with Redux
* Full stack application workflow
* Version control using Git & GitHub

---

## 📄 License

This project is created for **educational and learning purposes**.
