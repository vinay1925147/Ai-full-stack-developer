# 🛒 MERN E-Commerce Website

A full-stack E-Commerce web application built using the MERN Stack (MongoDB, Express.js, React.js, Node.js). The platform allows users to browse products, add items to the cart, place orders, and securely manage their accounts. It also includes an admin dashboard to manage products, orders, users, and categories.

---

# 🚀 Features

## 👤 User Features

### Authentication & Authorization
- User Registration
- User Login
- Secure JWT Authentication
- Password Hashing using bcrypt
- Protected Routes
- Logout Functionality

### User Profile
- View Profile
- Update Profile Information
- Change Password
- View Order History

### Product Management
- Browse All Products
- Search Products
- Filter Products by Category
- Filter by Price
- Sort Products
- Product Details Page
- Product Images
- Product Ratings & Reviews
- Stock Availability

### Shopping Cart
- Add Product to Cart
- Remove Product from Cart
- Update Quantity
- Cart Price Calculation
- Persistent Cart

### Wishlist
- Add to Wishlist
- Remove from Wishlist
- Move Wishlist Item to Cart

### Checkout
- Shipping Address
- Order Summary
- Payment Method Selection
- Order Confirmation

### Orders
- Place Order
- View My Orders
- Track Order Status
- Order Details

---

# 🔑 Admin Features

### Admin Dashboard
- Dashboard Overview
- Total Users
- Total Products
- Total Orders
- Total Revenue

### Product Management
- Add Product
- Edit Product
- Delete Product
- Upload Product Images
- Manage Product Categories
- Manage Stock

### Category Management
- Create Category
- Update Category
- Delete Category

### User Management
- View Users
- Delete Users
- Update User Role
- Block/Unblock Users

### Order Management
- View All Orders
- Update Order Status
- Cancel Orders
- Delivered Orders

---

# 💻 Tech Stack

## Frontend

- React.js
- React Router DOM
- Axios
- Context API / Redux Toolkit
- Tailwind CSS
- React Icons
- React Toastify

## Backend

- Node.js
- Express.js
- JWT Authentication
- bcrypt.js
- Multer
- Cloudinary (Optional)

## Database

- MongoDB
- Mongoose

---

# 📂 Project Structure

```
Ecommerce/
│
├── client/
│   ├── public/
│   ├── src/
│   │
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── layouts/
│   ├── redux/
│   ├── context/
│   ├── hooks/
│   ├── services/
│   ├── utils/
│   ├── App.jsx
│   └── main.jsx
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── uploads/
│   ├── utils/
│   ├── app.js
│   └── server.js
│
├── package.json
├── README.md
└── .gitignore
```

---

# 🗃️ Database Models

## User

- Name
- Email
- Password
- Phone
- Address
- Role
- Wishlist
- Orders

---

## Product

- Product Name
- Description
- Price
- Category
- Brand
- Images
- Stock
- Ratings
- Reviews

---

## Category

- Category Name
- Image

---

## Cart

- User
- Products
- Quantity
- Total Price

---

## Order

- User
- Shipping Address
- Products
- Payment Method
- Payment Status
- Order Status
- Total Amount

---



# 🔒 Authentication Flow

1. User Registers
2. Password is Hashed
3. User Logs In
4. JWT Token Generated
5. Token Stored
6. Protected Routes Access
7. Logout

---

# 🛍️ User Flow

```
Home
   ↓
Products
   ↓
Product Details
   ↓
Add to Cart
   ↓
Cart
   ↓
Checkout
   ↓
Payment
   ↓
Place Order
   ↓
Order Success
```

---

# ⚙️ Installation

## Install Frontend


cd client
npm install
```



## Install Backend

```bash
cd server
npm install
```

---


---

# Start Backend

```bash
cd server
npm run dev
```

---

# Start Frontend

```bash
cd client
npm run dev
```

---

# API Endpoints

## Authentication

```
POST   /api/auth/register
POST   /api/auth/login
GET    /api/auth/profile
PUT    /api/auth/update-profile
PUT    /api/auth/change-password
```

---

## Products

```
GET     /api/products
GET     /api/products/:id
POST    /api/products
PUT     /api/products/:id
DELETE  /api/products/:id
```

---

## Categories

```
GET     /api/categories
POST    /api/categories
PUT     /api/categories/:id
DELETE  /api/categories/:id
```

---

## Cart

```
GET     /api/cart
POST    /api/cart
PUT     /api/cart/:id
DELETE  /api/cart/:id
```

---


---

## Orders

```
POST    /api/orders
GET     /api/orders
GET     /api/orders/:id
PUT     /api/orders/:id
```

---



# Security Features

- JWT Authentication
- Password Hashing
- Protected API Routes
- Role-Based Authorization
- Secure Password Storage
- Input Validation
- Error Handling
- Environment Variables
- CORS Protection

---

# Future Improvements

- Stripe Payment Gateway
- Razorpay Integration
- PayPal Integration
- Coupon System
- Email Notifications
- Product Recommendations
- AI Search
- Inventory Analytics
- Sales Dashboard
- Dark Mode
- Multi-language Support
- Live Chat Support
- OTP Login
- Social Login
- PWA Support
- Mobile Application

---

# Screenshots

Add screenshots here.

```
Home Page

Products Page

Product Details

Cart

Checkout

Admin Dashboard

Orders

Profile
```

---


## Database

- MongoDB Atlas

---

# Performance Optimizations

- Lazy Loading
- Pagination
- Image Optimization
- Code Splitting
- API Caching
- Debounced Search
- Optimized MongoDB Queries

---

# Author

**Vinay Asati**







🛠️ Contribute by submitting a Pull Request

Thank you for visiting!
