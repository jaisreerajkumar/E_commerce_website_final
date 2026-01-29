Full Stack E-Commerce Web Application

Full-stack e-commerce web application developed to deliver a seamless online shopping experience for users and a powerful management system for administrators.
The application is designed using modern web technologies with a clear separation between user interface, admin dashboard, and backend services to ensure scalability, security, and maintainability.

---

## 📖 Project Description

This platform enables customers to browse products, manage carts, and place orders through an intuitive user interface.
An independent admin panel is provided for administrators to manage products, monitor orders, and maintain overall system control.
The backend API serves as the core of the application, handling authentication, business logic, and database communication.

This project follows real-world industry practices and demonstrates end-to-end full-stack development.

---

## 🎯 Objectives of the Project

* To build a real-world e-commerce application using modern technologies
* To implement secure user authentication and authorization
* To provide a dedicated admin dashboard for product and order management
* To design a scalable backend architecture using RESTful APIs
* To deploy frontend, admin, and backend services independently

---

## 🧠 Technology Stack

### Frontend (User & Admin)

* React.js
* JavaScript (ES6+)
* Tailwind CSS / CSS
* Axios
* Vercel for deployment

### Backend

* Node.js
* Express.js
* RESTful API architecture
* MongoDB (Database)
* JSON Web Token (JWT) for authentication
* Vercel for deployment

---

##Key Features

###User Features

* User registration and login
* Secure authentication using JWT
* Browse products with details
* Add products to cart
* Place orders
* View order history
* User session management

###Admin Features

* Admin authentication
* Dashboard overview
* Add new products
* Update existing products
* Delete products
* View all user orders
* Manage order status

---

##System Workflow

1. User accesses the frontend application
2. Frontend sends HTTP requests to backend APIs
3. Backend validates requests and performs business logic
4. Data is stored and retrieved from the database
5. Admin panel communicates with secured admin APIs
6. Changes are reflected in real time across the application
---

## 🗂️ Project Architecture

```text
E-Commerce-Web-Site/
│
├── frontend/        # User-facing UI
├── admin/           # Admin Dashboard
├── backend/         # Backend REST APIs
├── README.md
```

Each module is independently developed and deployed, ensuring modularity and scalability.

---

## ⚙️ Installation & Local Setup

### Clone the Repository

```bash
git clone https://github.com/indreshharshan/E-Commerce-Web-Site.git
cd E-Commerce-Web-Site
```

### Backend Setup

```bash
cd backend
npm install
npm run dev
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### Admin Panel Setup

```bash
cd admin
npm install
npm run dev
```

> Environment variables (`.env`) are required for database connection and authentication secrets.

---

## 📡 API Overview

| Method | Endpoint           | Description        |
| ------ | ------------------ | ------------------ |
| POST   | /auth/register     | Register new user  |
| POST   | /auth/login        | User login         |
| GET    | /products          | Fetch all products |
| POST   | /orders            | Place an order     |
| PUT    | /admin/product/:id | Update product     |
| DELETE | /admin/product/:id | Delete product     |

---

## 🔐 Security Implementation

* JWT-based authentication
* Protected routes for admin access
* Secure API request handling
* Environment variable protection

---

## 🚀 Deployment

* Frontend deployed using **Vercel**
* Admin panel deployed using **Vercel**
* Backend API deployed using **Vercel**
