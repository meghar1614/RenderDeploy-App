# RenderDeploy App

## 📌 Project Overview

**RenderDeploy App** is a full-stack web application that demonstrates deployment of a frontend and backend using Render, with a MongoDB database connection.

This project shows how to:

* Deploy a backend API
* Deploy a frontend application
* Connect both using REST APIs
* Use MongoDB as a cloud database
* Host everything using Render

---

## 🛠️ Technologies Used

* Frontend: HTML, CSS, JavaScript (React / Angular)
* Backend: Node.js, Express.js
* Database: MongoDB (MongoDB Atlas)
* Deployment: Render
* Version Control: GitHub

---

## 📂 Project Structure

```
RenderDeploy-App/
│
├── backend/
│   ├── server.js
│   ├── routes/
│   ├── models/
│   ├── package.json
│   └── ...
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
│
└── README.md
```

---

## ⚙️ Setup Instructions (Local)

### 1. Clone the Repository

```
git clone https://github.com/yourusername/renderdeploy-app.git
cd renderdeploy-app
```

---

### 2. Setup Backend

```
cd backend
npm install
npm start
```

---

### 3. Setup Frontend

```
cd frontend
npm install
npm start
```

---

## 🌐 Deployment

### 🔹 Backend Deployment (Render)

* Service Type: Web Service
* Build Command:

```
npm install
```

* Start Command:

```
npm start
```

---

### 🔹 Frontend Deployment (Render)

* Service Type: Static Site
* Build Command:

```
npm install && npm run build
```

* Publish Directory:

```
build
```

---

## 🔐 Environment Variables (Backend)

Add the following variables in Render:

```
MONGODB_URI=your_mongodb_connection_string
PORT=10000
JWT_SECRET=your_secret_key
```

---

## 🗄️ Database

* Database is hosted using MongoDB Atlas
* Connected via environment variables in backend

Example connection string:

```
mongodb+srv://username:password@cluster.mongodb.net/dbname
```

---

## 🔗 Live Links

* 🔹 Frontend URL:

```
https://your-frontend.onrender.com
```

* 🔹 Backend URL:

```
https://your-backend.onrender.com
```

---

## ✅ Features

* Full-stack architecture (Frontend + Backend)
* REST API communication
* MongoDB database integration
* Deployment on Render
* Environment-based configuration

---

## 🧪 Testing

* Backend tested using browser/Postman
* Frontend tested in browser
* Database verified in MongoDB Atlas

---

## ⚠️ Notes

* Ensure MongoDB URI is correct
* Backend must be deployed before frontend
* Update frontend API URL after backend deployment

---

## 👤 Author

* Name: Megha Patel
* Course: Web Development
* Project: RenderDeploy App

---

## 📌 Submission Checklist

* ✔ GitHub Repository Link
* ✔ Backend Render URL
* ✔ Frontend Render URL
* ✔ MongoDB Atlas Database

---
