# 🛒 E-Commerce Platform

A modern full-stack E-Commerce Platform built with React, Vite, Node.js, Express, PostgreSQL, and Prisma.

## 🚀 Overview

This project is a professional online shopping platform that allows customers to browse products, manage their cart, place orders, and track purchases. Administrators can manage products, categories, users, and orders through a dedicated dashboard.

---

## ✨ Features

### Customer Features
- 🔐 User Authentication (Login/Register)
- 👤 User Profile Management
- 🛍️ Product Browsing
- 🔎 Product Search & Filtering
- ❤️ Wishlist
- 🛒 Shopping Cart
- 💳 Checkout System
- 📦 Order Tracking
- 📜 Order History
- 🌙 Dark Mode Support

### Admin Features
- 📊 Dashboard Analytics
- 📦 Product Management
- 🏷️ Category Management
- 👥 User Management
- 📋 Order Management
- 💰 Sales Reports

---

## 🛠️ Tech Stack

### Frontend
- React
- Vite
- Tailwind CSS
- React Router
- Axios
- Framer Motion

### Backend
- Node.js
- Express.js
- JWT Authentication
- Multer

### Database
- PostgreSQL
- Prisma ORM

### Deployment
- Docker
- Nginx
- GitHub Actions

---

## 📁 Project Structure

```text
ecommerce-platform/
│
├── frontend/
│   ├── public/
│   └── src/
│       ├── assets/
│       ├── components/
│       ├── pages/
│       ├── admin/
│       ├── routes/
│       ├── services/
│       ├── hooks/
│       ├── context/
│       ├── store/
│       └── utils/
│
├── backend/
│   ├── src/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── routes/
│   │   ├── middleware/
│   │   ├── services/
│   │   ├── validators/
│   │   ├── prisma/
│   │   └── utils/
│   │
│   ├── uploads/
│   └── .env
│
├── database/
├── docs/
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/ecommerce-platform.git
cd ecommerce-platform
```

### Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

Frontend will run at:

```text
http://localhost:5173
```

### Backend Setup

```bash
cd backend

npm install

npm run dev
```

Backend will run at:

```text
http://localhost:5000
```

---

## 🗄️ Environment Variables

Create a `.env` file inside the backend directory:

```env
PORT=5000

DATABASE_URL="postgresql://username:password@localhost:5432/ecommerce_db"

JWT_SECRET=your_jwt_secret

JWT_EXPIRES_IN=7d
```

---

## 🧱 Database Migration

```bash
npx prisma migrate dev

npx prisma generate
```

---

## 🔑 User Roles

| Role | Permissions |
|--------|-------------|
| Customer | Browse products, order items, manage profile |
| Admin | Manage products, users, orders, analytics |

---

## 📸 Screenshots

### Home Page

Add screenshot here

### Product Page

Add screenshot here

### Admin Dashboard

Add screenshot here

---

## 📈 Future Enhancements

- AI Product Recommendations
- Product Reviews & Ratings
- Multi-Vendor Marketplace
- Real-Time Notifications
- Mobile Application
- Khmer Language Support
- Online Payment Gateway Integration

---

## 👨‍💻 Author

**Odom**

Student Developer | Full Stack Developer

GitHub: https://github.com/yourusername

---

## 📄 License

This project is licensed under the MIT License.

---

⭐ If you like this project, don't forget to star the repository.
