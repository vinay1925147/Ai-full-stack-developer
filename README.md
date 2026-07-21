# 🛒 MERN E-Commerce Website

A full-stack E-Commerce web application built using the MERN Stack (MongoDB, Express.js, React.js, Node.js). The platform allows users to browse products, add items to the cart, place orders, and securely manage their accounts. It also includes an admin dashboard to manage products, orders, users, and categories.

---

# 🚀 Features

## 👤 User Features

### Authentication & Authorization

### User Profile

### Product Management

### Shopping Cart

### Wishlist

### Checkout

### Orders



# 🔑 Admin Features

### Admin Dashboard

### Product Management

### Category Management

### User Management

### Order Management


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

# Screenshots

<img width="1366" height="768" alt="Screenshot (191)" src="https://github.com/user-attachments/assets/7ed9836a-3625-4317-9b75-358648d7d8de" />
<img width="1366" height="768" alt="Screenshot (192)" src="https://github.com/user-attachments/assets/eaa9f7d2-d405-4d7d-974c-3719f9c17c8c" />
<img width="1366" height="768" alt="Screenshot (193)" src="https://github.com/user-attachments/assets/dbce5dd9-37df-4e16-981e-89ab7cbb218e" />
<img width="1366" height="768" alt="Screenshot (194)" src="https://github.com/user-attachments/assets/e61a2f8c-1b3d-4466-bd2c-87ff289f997d" />
<img width="1366" height="768" alt="Screenshot (187)" src="https://github.com/user-attachments/assets/d0065e25-e786-493e-abd0-acaaa877e773" />
<img width="1366" height="768" alt="Screenshot (188)" src="https://github.com/user-attachments/assets/ffa1109a-c2d0-4b13-856a-40018b869a02" />
<img width="1366" height="768" alt="Screenshot (189)" src="https://github.com/user-attachments/assets/1b9c4df3-72ba-40c6-b787-ba1f31deb6f0" />
<img width="1366" height="768" alt="Screenshot (190)" src="https://github.com/user-attachments/assets/67f7c905-d1c2-4499-8a69-d8905cc3e0a9" />




# Author

**Vinay Asati**








