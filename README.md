# 🛒 BuyNest

A modern **E-Commerce Backend API** built using **Python** and **FastAPI**. BuyNest provides secure user authentication, product management, shopping cart functionality, and order processing through RESTful APIs.

The project is designed to demonstrate backend development skills, clean architecture, and database management using Python.

---

## 🚀 Features

### 🔐 Authentication

* User Registration
* User Login
* JWT Authentication
* Password Hashing (bcrypt)

### 👤 User Management

* View Profile
* Update Profile

### 📦 Product Management

* Add Product
* Update Product
* Delete Product
* View All Products
* View Product Details

### 📂 Categories

* Create Category
* View Categories

### 🛒 Shopping Cart

* Add Items to Cart
* Update Item Quantity
* Remove Items from Cart
* View Cart

### 📋 Orders

* Place Orders
* View Order History

---

# 🛠️ Tech Stack

| Category              | Technology    |
| --------------------- | ------------- |
| Language              | Python 3      |
| Framework             | FastAPI       |
| Database              | PostgreSQL    |
| ORM                   | SQLAlchemy    |
| Database Migration    | Alembic       |
| Authentication        | JWT           |
| Password Hashing      | bcrypt        |
| Validation            | Pydantic      |
| API Documentation     | Swagger UI    |
| Development Server    | Uvicorn       |
| Environment Variables | python-dotenv |
| API Testing           | Postman       |
| Version Control       | Git & GitHub  |

---

# 📁 Project Structure

```text
BuyNest/
│
├── app/
│   ├── auth/
│   ├── models/
│   ├── schemas/
│   ├── routes/
│   ├── database/
│   ├── core/
│   ├── utils/
│   └── main.py
│
├── alembic/
├── tests/
├── requirements.txt
├── .env
└── README.md
```

---

# ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/BuyNest.git
cd BuyNest
```

### Create a Virtual Environment

```bash
python -m venv venv
```

### Activate the Virtual Environment

**Windows**

```bash
venv\Scripts\activate
```

**macOS/Linux**

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Environment Variables

Create a `.env` file in the project root.

```env
DATABASE_URL=your_database_url
JWT_SECRET_KEY=your_secret_key
ALGORITHM=HS256
ACCESS_TOKEN_EXPIRE_MINUTES=30
```

### Run Database Migrations

```bash
alembic upgrade head
```

### Start the Development Server

```bash
uvicorn app.main:app --reload
```

---

# 📄 API Documentation

Once the server is running, visit:

* **Swagger UI:** `http://127.0.0.1:8000/docs`
* **ReDoc:** `http://127.0.0.1:8000/redoc`

---

# 🎯 Future Enhancements

* Wishlist
* Product Reviews & Ratings
* Coupon System
* Payment Gateway Integration
* Image Uploads
* Admin Dashboard
* Docker Support
* Redis Caching

---

# 👨‍💻 Author

**Lathiga MK**

Backend Developer | Python & FastAPI Enthusiast
