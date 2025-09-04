# Thegallery
A full-stack web application designed to showcase and sell handmade charms online. The main objective of this project is to implement a backend-focused architecture while still providing a functional frontend for end users.

## 📌 Features

### 🔐 Backend (Core Focus)
* **User Authentication & Authorization** (JWT-based login/signup)
* **Product Management** (add, update, delete charms – admin only)
* **Order Management** (place orders, track status)
* **Cart System** (add/remove charms to cart)
* **RESTful API** for frontend consumption
* **Database Integration** (persistent data storage)
* **Validation & Error Handling** for secure and reliable backend

### 🎨 Frontend (Minimal but Functional)

* Homepage with charms listing
* Product details page
* Shopping cart UI
* Checkout page
* Simple admin dashboard (manage products)

---

## 🛠️ Tech Stack

**Backend**

* Node.js + Express.js
* MongoDB (Mongoose ORM)
* JWT for authentication
* bcrypt for password hashing

**Frontend**

* React.js (with hooks & context API)
* TailwindCSS for styling

**Other Tools**

* Postman (API testing)
* Git & GitHub (version control)
* dotenv (environment variables)

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/charms-store.git
cd charms-store
```

### 2️⃣ Setup Backend

```bash
cd backend
npm install
```

Create a `.env` file in `backend/` with:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Run server:

```bash
npm run dev
```

### 3️⃣ Setup Frontend

```bash
cd ../frontend
npm install
npm start
```

---

## 📡 API Endpoints

### Auth

* `POST /api/auth/register` – Register new user
* `POST /api/auth/login` – Login user

### Products

* `GET /api/products` – Get all charms
* `POST /api/products` – Add new charm (admin)
* `PUT /api/products/:id` – Update charm (admin)
* `DELETE /api/products/:id` – Delete charm (admin)

### Cart

* `POST /api/cart` – Add to cart
* `GET /api/cart` – Get user cart
* `DELETE /api/cart/:id` – Remove from cart

### Orders

* `POST /api/orders` – Place order
* `GET /api/orders` – Get user orders

---

## 🧩 Future Improvements

* Payment gateway integration (Stripe/PayPal)
* Search & filters for products
* Wishlist functionality
* Email notifications for orders
* Admin analytics dashboard

---

## 👩‍💻 Author

**Anga’s Gallery** – Handmade charms collection
By Gannon Mossang

---
