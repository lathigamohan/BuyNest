# 🛍️ BuyNest

A modern e-commerce backend built with **Node.js**, **Express.js**, **TypeScript**, **PostgreSQL**, and **Prisma**.

The project focuses on clean architecture, authentication, product management, shopping cart functionality, and order processing.

---

## 🚀 Features

### Authentication
- User Registration
- User Login
- JWT Authentication
- Password Hashing

### Users
- View Profile
- Update Profile

### Products
- Create Product
- Update Product
- Delete Product
- Get All Products
- Get Product by ID

### Categories
- Create Category
- View Categories

### Cart
- Add to Cart
- Update Quantity
- Remove from Cart

### Orders
- Place Order
- View Order History

---

## 🛠 Tech Stack

- Node.js
- Express.js
- TypeScript
- PostgreSQL
- Prisma ORM
- JWT
- Bcrypt

---

## 📁 Project Structure

```
src/
│
├── modules/
│   ├── auth/
│   ├── users/
│   ├── products/
│   ├── categories/
│   ├── cart/
│   └── orders/
│
├── middleware/
├── routes/
├── prisma/
└── app.ts
```

---

## ⚙️ Installation

```bash
git clone https://github.com/yourusername/shopsphere.git

cd shopsphere

npm install
```

Create a `.env` file:

```env
DATABASE_URL=
JWT_SECRET=
PORT=5000
```

Run migrations:

```bash
npx prisma migrate dev
```

Start the server:

```bash
npm run dev
```

---

## 📌 Future Improvements

- Wishlist
- Payment Gateway
- Reviews & Ratings
- Admin Dashboard
- Redis Caching
- Docker
- Swagger Documentation

---

## 👨‍💻 Author

**Lathiga MK**
