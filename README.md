# 🛒 Multi-Vendor E-commerce Platform (Headless + HTMX)

## 🚀 Overview

This project is a **multi-vendor e-commerce platform** built with **Django**, **Django REST Framework**, and **HTMX**.

It allows vendors to create shops, upload products, and manage orders, while customers can browse products, add items to cart, and place orders.

The system is designed with a **headless API architecture** (for mobile apps) and a **modern responsive frontend**.

---

## ✨ Features

### 🛍️ Marketplace (Public)

* Browse products without login
* Jumia-style product listing UI
* Add to cart system (session-based)

### 🔐 Authentication System

* Separate login and registration pages
* User session handling
* Logout functionality

### 🧑‍💼 Vendor Dashboard

* Create and manage shops
* Add and manage products
* Upload product images
* Stripe-style dashboard layout

### 🛒 Cart & Checkout

* Add/remove items from cart
* View cart summary
* Checkout to create orders

### 🖼️ Media Upload

* Product image upload support
* Media file handling via Django

### 🔌 API (Headless)

* REST API endpoints for:

  * Shops
  * Products
  * Orders
* Ready for mobile app integration

---

## 🛠 Tech Stack

### Backend

* Django
* Django REST Framework
* SQLite (default)

### Frontend

* HTML
* TailwindCSS
* HTMX
* Bootstrap (optional components)

---

## 📁 Project Structure

```
ecommerce/
│
├── accounts/        # Authentication (login/register)
├── core/            # Homepage (marketplace)
├── dashboard/       # Vendor dashboard
├── shops/           # Shop management
├── products/        # Product management
├── orders/          # Cart & orders
├── api/             # REST API
│
├── templates/
├── static/
├── media/
```

---

## 🔗 Key Routes

| Route         | Description          |
| ------------- | -------------------- |
| `/`           | Marketplace (public) |
| `/login/`     | Login page           |
| `/register/`  | Registration page    |
| `/dashboard/` | Vendor dashboard     |
| `/cart/`      | Shopping cart        |
| `/checkout/`  | Checkout             |

---

## ▶️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

### 2. Create virtual environment

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run migrations

```bash
python manage.py migrate
```

### 5. Create superuser

```bash
python manage.py createsuperuser
```

### 6. Run server

```bash
python manage.py runserver
```

---

## 📸 Screenshots

(Add screenshots here: homepage, dashboard, cart, etc.)

---

## 🧠 Learning Objectives

This project demonstrates:

* Full-stack Django development
* REST API design
* Authentication & authorization
* Session-based cart system
* HTMX for dynamic UI
* Responsive UI design

---

## 🔮 Future Improvements

* Payment integration (Paystack / Stripe)
* Product reviews & ratings
* Real-time notifications
* Mobile app integration
* Advanced analytics dashboard

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

Built by [Your Name]

---

## ⭐ Support

If you like this project, please give it a ⭐ on GitHub!
