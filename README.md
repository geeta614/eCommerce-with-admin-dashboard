# 🛒 E-Commerce with Admin Dashboard

A powerful full-stack E-Commerce web application with a sleek and responsive UI. This platform supports both **user** and **admin** roles, complete with real-time analytics, product management, and secure authentication.

---

## 🚀 Tech Stack

### 🔧 Backend
- **Express.js**
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
- ✅ User Registration and Login
- ✅ Browse products by category
- ✅ View featured and recommended products
- ✅ Add unlimited products to cart
- ✅ Seamless experience

### 🛠️ Admin Features
- 🔐 Secure Admin Login
- ➕ Add New Products
- ❌ Delete Products
- ⭐ Feature or Unfeature Products
- 📊 Dashboard with Real-Time Analytics:
  - Total Users
  - Orders
  - Sales and Revenue
- 👥 Role-Based Access: Admin vs User

---

## 📸 Demo Screenshots

> All screenshots are for demonstration purposes and simulate real-time interactions.

### 🧑 User Interface

<p align="center">
  <img src="Photos/1. Home Page.png" alt="Home Page" width="600" />
  <br/><strong>Home Page</strong><br/><br/>

  <img src="Photos/2. SignUp.png" alt="Sign Up" width="600" />
  <br/><strong>Sign Up Page</strong><br/><br/>

  <img src="Photos/3. Password must be atleast 6 characters long.png" alt="Password Validation" width="600" />
  <br/><strong>Password Validation Error</strong><br/><br/>

  <img src="Photos/4. Login.png" alt="Login Page" width="600" />
  <br/><strong>Login Page</strong><br/><br/>

  <img src="Photos/5. Logged in page.png" alt="User Dashboard" width="600" />
  <br/><strong>Logged-In User Dashboard</strong><br/><br/>

  <img src="Photos/6. Tshirt page.png" alt="Product Category Page" width="600" />
  <br/><strong>T-Shirt Category Page</strong><br/><br/>

  <img src="Photos/7. Final cart page.png" alt="Cart Page" width="600" />
  <br/><strong>Cart Page</strong><br/><br/>

  <img src="Photos/8. Featuring products.png" alt="Featured Products" width="600" />
  <br/><strong>Featured Products Recommended</strong><br/><br/>

  <img src="Photos/9. Purchase successful.png" alt="Purchase Confirmation" width="600" />
  <br/><strong>Purchase Confirmation</strong><br/><br/>
</p>

### 👩‍💼 Admin Dashboard

<p align="center">
  <img src="Photos/11. Home Page.png" alt="Admin Home Page" width="600" />
  <br/><strong>Admin Home Page</strong><br/><br/>

  <img src="Photos/12. Login with admin credentials.png" alt="Admin Login" width="600" />
  <br/><strong>Admin Login</strong><br/><br/>

  <img src="Photos/13. Dashboard available.png" alt="Admin Overview" width="600" />
  <br/><strong>Admin Dashboard Overview</strong><br/><br/>

  <img src="Photos/14. Admin dashboard.png" alt="Admin Dashboard Details" width="600" />
  <br/><strong>Detailed Dashboard Metrics</strong><br/><br/>

  <img src="Photos/15. Create new product.png" alt="Add Product Form" width="600" />
  <br/><strong>Add New Product (Admin)</strong><br/><br/>

  <img src="Photos/16. Feature or Remove products.png" alt="Manage Products" width="600" />
  <br/><strong>Manage Featured Products and Remove Products</strong><br/><br/>

  <img src="Photos/17. Analytics.png" alt="Analytics Panel" width="600" />
  <br/><strong>Sales & User Analytics</strong><br/><br/>
</p>

---

## 📹 Demo Video

> _You can embed your YouTube demo video or replace the link below._

🎥 [Watch Full Demo on Linkdln](https://www.youtube.com/watch?v=your-demo-link)

---

## 🛠️ Installation & Setup

Follow these steps to set up the project locally.

### 1. Clone the Repository

```
# Using HTTPS
git clone https://github.com/your-username/your-repo-name.git

# OR Using SSH
git clone git@github.com:your-username/your-repo-name.git
```

### 2. Install Dependencies

```
📦 Backend
cd backend
npm install

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

```
▶️ Backend
cd backend
npx nodemon server.js

▶️ Frontend
cd frontend
npm run dev
```

## ✅ Running URLs

```
Frontend:
http://localhost:5173/

Backend:
http://localhost:5000/
```
