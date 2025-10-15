# 🛒 Simple E-Commerce Project

## 📖 Overview

This is a simple **E-Commerce website** built for learning purposes.
The project allows users to view products, register, log in, add items to the cart, and place orders.
It’s built using **PHP (Backend)**, **SQL Server (Database)**, and **HTML/CSS/JavaScript (Frontend)**.

---

## ⚙️ Technologies Used

* 🧩 **Frontend:** HTML, CSS, JavaScript
* ⚙️ **Backend:** PHP
* 🗄️ **Database:** SQL Server (Local)
* 🔄 **Version Control:** Git & GitHub

---

## 🧠 Features

* View product list
* View product details
* Register and log in
* Add products to cart
* Checkout (basic order form)

---

## 🧱 Database Structure

Main tables used:

1. **Products** → stores product info (name, price, image, description)
2. **Users** → stores registered users
3. **Orders** → stores order details

---

## 🚀 How to Run the Project

1. Install **XAMPP or WAMP** to run PHP locally.
2. Create a database in **SQL Server** (you can use `localhost`).
3. Import the provided SQL file (if exists).
4. Place the project folder inside `htdocs` (XAMPP) or `www` (WAMP).
5. Run the project from your browser:

   ```
   http://localhost/ecommerce/
   ```

---

## 🧩 Folder Structure

```
/ecommerce
│
├── models/
│   └── ProductModel.php
│
├── controllers/
│   └── ProductController.php
│
├── views/
│   └── productsView.php
│
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
│
└── index.php
```

---
