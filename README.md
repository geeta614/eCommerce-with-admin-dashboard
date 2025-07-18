# 🛒 E-Commerce with Admin Dashboard

A full-stack E-commerce web application with an intuitive user interface, featuring user and admin roles, real-time analytics, Stripe integration, and dynamic product management.

## 🚀 Tech Stack

### 🔧 Backend
- **Express**
- **Mongoose**
- **bcryptjs**
- **jsonwebtoken**
- **dotenv**
- **cookie-parser**
- **cloudinary**
- **ioredis**

### 🎨 Frontend
- **React 19**
- **React Router DOM v7**
- **Axios**
- **Framer Motion**
- **Lucide React**
- **React Hot Toast**
- **Recharts**
- **React Confetti**
- **Zustand**

---

## ✨ Features

### 👥 User Features
- ✅ Sign Up / Login
- ✅ Browse products by category
- ✅ View featured products
- ✅ Add any number of products to cart
- ✅ Make payments via Stripe

### 🛠️ Admin Features
- 🔐 Admin login
- ➕ Add new products
- ❌ Delete products
- ⭐ Set products as featured
- 📊 View analytics:
  - Total users
  - Orders
  - Sales & Revenue
- 👥 Role-based access: Admin & User

---

## 🖼️ Demo

### 📸 Screenshots
> _Add your screenshots in a `/screenshots` folder and embed them like this:_

![Home Page](./screenshots/homepage.png)
![Admin Dashboard](./screenshots/admin-dashboard.png)

### 📹 Demo Video
> _Embed your demo video (hosted on YouTube or local path)_

[Watch Demo on YouTube](https://www.youtube.com/watch?v=your-demo-link)

---

## 🛠️ Installation & Setup

Follow these steps to set up the project locally.

### 1Clone the Repository
```Bash
# HTTPS
git clone https://github.com/your-username/your-repo-name.git

# OR SSH
git clone git@github.com:your-username/your-repo-name.git
```
2. Install Dependencies
📦 Backend
```
cd backend
npm install
```
```
📦 Frontend
cd frontend
npm install
```
### 3. Configure Environment Variables
Create a .env file inside the backend folder with the following variables:

```

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
```
4. Run the Project
▶️ Backend
```
cd backend
npx nodemon server.js
```
▶️ Frontend
```
cd frontend
npm run dev
```
✅ Running URLs
```
Frontend: http://localhost:5173/

Backend: http://localhost:5000/
```
