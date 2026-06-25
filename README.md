# 🛒 E-Commerce Platform

![React](https://img.shields.io/badge/React-Frontend-61DAFB?logo=react)
![Vite](https://img.shields.io/badge/Vite-Build_Tool-646CFF?logo=vite)
![Node.js](https://img.shields.io/badge/Node.js-Backend-339933?logo=node.js)
![Express.js](https://img.shields.io/badge/Express.js-API-000000?logo=express)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-4169E1?logo=postgresql)
![Prisma](https://img.shields.io/badge/Prisma-ORM-2D3748?logo=prisma)
![License](https://img.shields.io/badge/License-MIT-green)

A modern, scalable, and responsive E-Commerce Platform built using React, Vite, Node.js, Express.js, PostgreSQL, and Prisma ORM.

---

## 📖 Project Overview

This project is designed to provide a complete online shopping experience for customers and a powerful management dashboard for administrators.

The platform includes product browsing, shopping cart functionality, secure authentication, order management, and an admin dashboard for managing products, users, and sales.

---

## ✨ Features

### 👤 Customer Features

- User Registration
- User Login & Authentication
- JWT Authentication
- Profile Management
- Product Search
- Product Filtering
- Product Categories
- Product Details
- Shopping Cart
- Wishlist
- Checkout System
- Order History
- Order Tracking
- Responsive Design
- Dark Mode

---

### 🔧 Admin Features

- Admin Dashboard
- Manage Products
- Manage Categories
- Manage Orders
- Manage Users
- Inventory Management
- Sales Analytics
- Customer Management

---

## 🛠️ Technology Stack

### Frontend

- React
- Vite
- Tailwind CSS
- React Router DOM
- Axios
- Framer Motion

### Backend

- Node.js
- Express.js
- JWT Authentication
- Bcrypt.js
- Multer

### Database

- PostgreSQL
- Prisma ORM

### Development Tools

- Git
- GitHub
- Postman
- VS Code

---

## 📁 Project Structure

```text
E-commerce-Platform/
│
├── frontend/
│   │
│   ├── public/
│   │
│   └── src/
│       │
│       ├── assets/
│       ├── components/
│       ├── pages/
│       ├── admin/
│       ├── layouts/
│       ├── routes/
│       ├── services/
│       ├── hooks/
│       ├── context/
│       ├── store/
│       ├── utils/
│       ├── App.jsx
│       └── main.jsx
│
├── backend/
│   │
│   ├── src/
│   │   │
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── routes/
│   │   ├── middleware/
│   │   ├── services/
│   │   ├── validators/
│   │   ├── utils/
│   │   ├── prisma/
│   │   ├── app.js
│   │   └── server.js
│   │
│   └── uploads/
│
├── docs/
├── database/
├── README.md
└── .gitignore
```

---

## 🗄️ Database Design

### Users

```text
id
name
email
password
role
created_at
```

### Categories

```text
id
name
created_at
```

### Products

```text
id
category_id
name
description
price
stock
image
created_at
```

### Orders

```text
id
user_id
total_price
status
created_at
```

### OrderItems

```text
id
order_id
product_id
quantity
price
```

### Payments

```text
id
order_id
amount
method
status
```

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/OdomCH/E-commerce-Platform.git

cd E-commerce-Platform
```

---

## 📦 Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

Frontend URL:

```text
http://localhost:5173
```

---

## ⚙️ Backend Setup

```bash
cd backend

npm install

npm run dev
```

Backend URL:

```text
http://localhost:5000
```

---

## 🔐 Environment Variables

Create a `.env` file inside the backend folder.

```env
PORT=5000

DATABASE_URL="postgresql://username:password@localhost:5432/ecommerce_db"

JWT_SECRET=your_super_secret_key

JWT_EXPIRES_IN=7d
```

---

## 🧱 Prisma Setup

Generate Prisma Client:

```bash
npx prisma generate
```

Run Migration:

```bash
npx prisma migrate dev
```

Open Prisma Studio:

```bash
npx prisma studio
```

---

## 📷 Screenshots

### Home Page

Add screenshot here

---

### Product Page

Add screenshot here

---

### Shopping Cart

Add screenshot here

---

### Admin Dashboard

Add screenshot here

---

## 🔮 Future Improvements

- AI Product Recommendations
- Product Reviews & Ratings
- Email Notifications
- Multi-language Support
- Khmer Language Support
- Stripe Payment Integration
- PayPal Integration
- Mobile Application
- Docker Deployment
- Cloud Hosting

---

## 🎯 Learning Objectives

This project demonstrates:

- Frontend Development with React
- RESTful API Development
- Authentication & Authorization
- Database Design
- State Management
- Full Stack Development
- Software Architecture
- Deployment Workflow

---

## 👨‍💻 Developer

### OdomCH

Software Engineering Student

Passionate about:

- Full Stack Development
- Cloud Computing
- Web Technologies
- Database Systems
- Software Architecture

GitHub Profile:

👉 https://github.com/OdomCH

Project Repository:

👉 https://github.com/OdomCH/E-commerce-Platform

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

Feel free to fork this repository and submit a pull request.

---

## ⭐ Support

If you like this project, please consider giving it a star ⭐ on GitHub.

---

## 📄 License

This project is licensed under the MIT License.

Copyright © 2026 OdomCH

---

### Built with ❤️ by OdomCH
