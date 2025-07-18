# 🛒 E-Commerce with Admin Dashboard

A full-stack E-commerce web application with an intuitive user interface, featuring user and admin roles, real-time analytics, and dynamic product management.

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
## 📸 Demo Screenshots

### Role: User

<div style="width: 100%; overflow-x: auto; white-space: nowrap; padding-bottom: 15px; box-sizing: border-box;">
  <img src="Photos/1. Home Page.png" alt="Home Page Screenshot" style="height: 250px; margin-right: 15px; display: inline-block; vertical-align: middle;">
  <img src="Photos/2. SignUp.png" alt="Sign Up Page Screenshot" style="height: 250px; margin-right: 15px; display: inline-block; vertical-align: middle;">
  <img src="Photos/3. Password must be atleast 6 characters long.png" alt="Password Validation Error" style="height: 250px; margin-right: 15px; display: inline-block; vertical-align: middle;">
  <img src="Photos/4. Login.png" alt="Login Page Screenshot" style="height: 250px; margin-right: 15px; display: inline-block; vertical-align: middle;">
  <img src="Photos/5. Logged in page.png" alt="Logged-in User Dashboard" style="height: 250px; margin-right: 15px; display: inline-block; vertical-align: middle;">
  <img src="Photos/6. Tshirt page.png" alt="T-shirt Product Page" style="height: 250px; margin-right: 15px; display: inline-block; vertical-align: middle;">
  <img src="Photos/7. Final cart page.png" alt="Shopping Cart Page" style="height: 250px; margin-right: 15px; display: inline-block; vertical-align: middle;">
  <img src="Photos/8. Featuring products.png" alt="Featured Products Section" style="height: 250px; margin-right: 15px; display: inline-block; vertical-align: middle;">
  <img src="Photos/9. Purchase successful.png" alt="Purchase Confirmation Page" style="height: 250px; margin-right: 15px; display: inline-block; vertical-align: middle;">
</div>

### Role: Admin

<div style="width: 100%; overflow-x: auto; white-space: nowrap; padding-bottom: 15px; box-sizing: border-box;">
  <img src="Photos/11. Home Page.png" alt="Home Page (Alternative View)" style="height: 250px; margin-right: 15px; display: inline-block; vertical-align: middle;">
  <img src="Photos/12. Login with admin credentials.png" alt="Admin Login Page" style="height: 250px; margin-right: 15px; display: inline-block; vertical-align: middle;">
  <img src="Photos/13. Dashboard available.png" alt="Admin Dashboard Overview" style="height: 250px; margin-right: 15px; display: inline-block; vertical-align: middle;">
  <img src="Photos/14. Admin dashboard.png" alt="Detailed Admin Dashboard" style="height: 250px; margin-right: 15px; display: inline-block; vertical-align: middle;">
  <img src="Photos/15. Create new product.png" alt="Create New Product Form (Admin)" style="height: 250px; margin-right: 15px; display: inline-block; vertical-align: middle;">
  <img src="Photos/16. Feature or Remove products.png" alt="Admin Product Management" style="height: 250px; margin-right: 15px; display: inline-block; vertical-align: middle;">
  <img src="Photos/17. Analytics.png" alt="Admin Analytics Page" style="height: 250px; margin-right: 15px; display: inline-block; vertical-align: middle;">
</div>

## 📹 Demo Video
> _Embed your demo video (hosted on YouTube or local path)_

[Watch Demo on YouTube](https://www.youtube.com/watch?v=your-demo-link)

---

## 🛠️ Installation & Setup

Follow these steps to set up the project locally.

### 1. Clone the Repository
```Bash
# HTTPS
git clone https://github.com/your-username/your-repo-name.git

# OR SSH
git clone git@github.com:your-username/your-repo-name.git
```
### 2. Install Dependencies
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
```

### 4. Run the Project
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
Frontend:
```
http://localhost:5173/
```
Backend:
```
http://localhost:5000/
```
