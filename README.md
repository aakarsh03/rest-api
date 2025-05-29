# 📦 REST API - Node.js, Express, MongoDB

A scalable RESTful API built with **Node.js**, **Express**, and **MongoDB** for efficient subscriber management.

🔗 A production-ready RESTful API built using the MERN stack's backend technologies — **Express.js** and **MongoDB** — showcasing clean architecture, middleware usage, schema modeling, and asynchronous programming with **Promises** and **async/await**.

---

## 🚀 Project Overview

This project is a fully functional **RESTful API** designed to manage **subscriber data** using Node.js and Express. The API provides full **CRUD operations** and is backed by **MongoDB** using **Mongoose** for schema validation and data handling. The application is designed to be:

- 🔒 Secure
- ⚙️ Scalable
- 🧩 Modular
- 🛡 Robust

It includes **built-in error handling** and structured **middleware functions** to manage data flow efficiently.

---

## ✅ Features

📚 **Full CRUD Functionality**  
Create, Read, Update, and Delete operations for subscriber data.

🔁 **Async/Await & Promises**  
Handles asynchronous requests gracefully using modern JavaScript features.

🧱 **Schema Validation with Mongoose**  
Ensures data integrity through Mongoose schema models.

🧩 **Modular Routing with Express Router**  
Cleanly separates logic and organizes route handlers.

⚠️ **Robust Error Handling**  
Try-catch blocks and proper HTTP status codes for production-level stability.

🔐 **Environment Configuration via `.env`**  
Keeps sensitive information secure and separate from codebase.

---



## 🛠 Tech Stack

- **Node.js** – Runtime environment
- **Express.js** – Lightweight web framework
- **MongoDB** – NoSQL database
- **Mongoose** – MongoDB ODM (Object Data Modeling)
- **dotenv** – Secure environment configuration
- **Postman / REST Client** – API testing tools

---

## 📫 Endpoints

| Method | Endpoint              | Description               |
|--------|------------------------|---------------------------|
| GET    | `/subscribers`         | Get all subscribers       |
| GET    | `/subscribers/:id`     | Get subscriber by ID      |
| POST   | `/subscribers`         | Add a new subscriber      |
| PATCH  | `/subscribers/:id`     | Update subscriber data    |
| DELETE | `/subscribers/:id`     | Delete subscriber         |

---

## 🧪 How to Test

Test the API using:

- [x] **Postman**
- [x] **VS Code REST Client** extension

Make sure your server is running on `http://localhost:3000` (or your configured port).

---

## 🧰 Setup Instructions

```bash
# 1. Clone the repo
git clone https://github.com/your-username/subscriber-api.git

# 2. Navigate into the folder
cd subscriber-api

# 3. Install dependencies
npm install

# 4. Set up environment variables
touch .env
# Add your MongoDB URL inside .env
MONGODB_URL=your_mongodb_connection_string

# 5. Start the server
npm start
