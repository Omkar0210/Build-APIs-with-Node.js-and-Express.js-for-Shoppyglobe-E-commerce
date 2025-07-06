

# 🛍️ ShoppyGlobe E-commerce App

A full-stack e-commerce app with product listings, cart functionality, and user authentication.

## Table of Contents
- [Tech Stack](#-tech-stack)
- [Features](#-features)
- [MongoDB Integration](#️-mongodb-integration)
- [Folder Structure](#-folder-structure)
- [Installation](#-installation)
- [Author](#-author)

## 🚀 Tech Stack
- **Frontend:** React, Tailwind CSS, Axios, React Router
- **Backend:** Node.js, Express, MongoDB (Atlas)
- **Authentication:** JWT

## 🧾 Features
- User login & signup
- Browse products
- Add to cart (protected route)
- Dynamic cart count & user info
- Protected checkout route

## 🗄️ MongoDB Integration
**Database:** `test`

**Collections:**
- `products`: Stores product data (name, price, description, stock)
- `carts`: Stores cart items (product IDs and quantities)
- `users`: Stores user authentication data

**CRUD operations implemented for:**
- **Products:** Create, Read, Update, Delete
- **Cart Items:** Add to Cart, Update Quantity, Remove Items, Clear Cart




## 🔧 Folder Structure

```plaintext
shoppyglobe/
├── backend/
│   ├── config/
│   │   └── db.js
│   ├── controllers/
│   │   ├── authController.js
│   │   ├── cartController.js
│   │   ├── productController.js
│   │   └── userController.js
│   ├── middleware/
│   │   ├── authMiddleware.js
│   │   ├── errorMiddleware.js
│   │   └── notFound.js
│   ├── models/
│   │   ├── Cart.js
│   │   ├── Product.js
│   │   ├── User.js
│   ├── routes/
│   │   ├── authRoutes.js
│   │   ├── cartRoutes.js
│   │   ├── productRoutes.js
│   │   └── userRoutes.js
│   ├── .env
│   ├── server.js
│   ├── package.json
│   └── package-lock.json
│
├── frontend/
│   ├── public/
│   │   ├── favicon.jpeg
│   │   └── vite.svg
│   ├── src/
│   │   ├── api/
│   │   │   └── cartAPI.js
│   │   ├── assets/
│   │   ├── components/
│   │   │   ├── Auth/
│   │   │   │   ├── Login.jsx
│   │   │   │   └── Signup.jsx
│   │   │   ├── Cart/
│   │   │   │   ├── Cart.jsx
│   │   │   │   ├── CartItem.jsx
│   │   │   │   └── Checkout.jsx
│   │   │   ├── Product/
│   │   │   │   ├── ProductDetail.jsx
│   │   │   │   ├── ProductItem.jsx
│   │   │   │   └── ProductList.jsx
│   │   │   └── Shared/
│   │   │       ├── Footer.jsx
│   │   │       ├── Header.jsx
│   │   │       └── LoadingSpinner.jsx
│   │   ├── context/
│   │   │   ├── AuthContext.jsx
│   │   │   └── CartContext.jsx
│   │   ├── hooks/
│   │   │   └── useFetch.js
│   │   ├── utils/
│   │   │   ├── axiosAuth.js
│   │   │   └── axiosInstance.js
│   │   ├── App.jsx
│   │   ├── App.css
│   │   ├── main.jsx
│   │   ├── index.css
│   │   └── index.html
│   ├── vite.config.js
│   ├── package.json
│   └── package-lock.json
│
└── README.md

```

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone "https://github.com/Omkar0210/Build-APIs-with-Node.js-and-Express.js-for-Shoppyglobe-E-commerce.git"
   cd shoppyglobe-fullStack
   ```

2. Install dependencies for the backend:
   ```bash
   cd backend
   npm install
   npm start
   ```

3. Install dependencies for the frontend:
   ```bash
   cd frontend
   npm install
   npm run dev
   ```

4. Open the app in your browser at `http://localhost:5173`.


## 👤 Author
**Gunjal Omkar**

- [LinkedIn] = https://www.linkedin.com/in/omkar-gunjal-8b4b46252/
- [GitHub]   = https://github.com/Omkar0210
