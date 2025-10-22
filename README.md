# 🛍️ E-Commerce Fullstack Application (Spring Boot + Angular + AWS)

A comprehensive **full-stack e-commerce platform** built with **Spring Boot**, **Angular**, and **AWS Cloud Services**, featuring secure authentication, RESTful APIs, and a modern responsive UI.

---

## 🌟 Overview

This project demonstrates a fully functional **e-commerce system** that integrates a robust **Spring Boot backend** with a dynamic **Angular frontend**.
It supports **JWT-based authentication**, **role-based access control**, and **AWS cloud deployment** for scalability and high performance.

---

## ⚙️ Features

### 🧩 Backend

* Developed using **Spring Boot** and **Spring Data JPA**
* Implements **Spring Security 6** with **JWT authentication**
* Provides **RESTful APIs** for user, product, cart, and order management
* Integrated with **PostgreSQL** database
* Follows **layered architecture (Controller → Service → Repository)**

### 💻 Frontend

* Built with **Angular** and **Bootstrap 5** for responsive design
* Connects seamlessly with backend REST APIs
* Includes **JWT-based session management**
* Supports **role-based routing (User / Admin)**

---

## 🗂️ Project Structure

```
e-commerce-fullstack_springboot_angular_aws/
│── e-commerce-backend/
│   ├── src/main/java/...
│   ├── src/main/resources/
│   ├── pom.xml
│
│── e-commerce-frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│
│── README.md
│── .gitignore
│── docker-compose.yml
```

---

## 🚀 Setup & Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/dinesh-more/e-commerce-fullstack_springboot_angular_aws.git
cd e-commerce-fullstack_springboot_angular_aws
```

### 2️⃣ Backend Setup

```bash
cd e-commerce-backend
# Update your database credentials in application.properties or application.yml
mvn spring-boot:run
```

### 3️⃣ Frontend Setup

```bash
cd e-commerce-frontend
npm install
ng serve
```

---

## 🔗 REST API Endpoints

| Method     | Endpoint                     | Description                       |
| ---------- | ---------------------------- | --------------------------------- |
| **POST**   | `/api/auth/signup`           | Register a new user               |
| **POST**   | `/api/auth/login`            | User login                        |
| **POST**   | `/api/products`              | Add a new product                 |
| **GET**    | `/api/products`              | Retrieve all products             |
| **GET**    | `/api/products/{id}`         | Get product details               |
| **PUT**    | `/api/products/{id}`         | Update product information        |
| **DELETE** | `/api/products/{id}`         | Delete a product                  |
| **POST**   | `/api/cart`                  | Add item to cart                  |
| **GET**    | `/api/cart`                  | Get all cart items                |
| **DELETE** | `/api/cart/{productId}`      | Remove item from cart             |
| **POST**   | `/api/orders`                | Place a new order                 |
| **GET**    | `/api/orders`                | Fetch all orders for a user       |
| **GET**    | `/api/orders/{orderId}`      | Get specific order details        |
| **PUT**    | `/api/orders/{orderId}/pay`  | Mark order as paid                |
| **PUT**    | `/api/orders/{orderId}/ship` | Mark order as shipped (**Admin**) |
| **GET**    | `/api/users`                 | View all users (**Admin**)        |
| **GET**    | `/api/users/{userId}`        | Get user details (**Admin**)      |
| **PUT**    | `/api/users/{userId}`        | Update user info (**Admin**)      |
| **DELETE** | `/api/users/{userId}`        | Delete user (**Admin**)           |

---

## 🛠️ Tech Stack

### 🔹 Backend

* Spring Boot
* Spring Data JPA
* Spring Security 6 + JWT
* PostgreSQL
* Maven

### 🔹 Frontend

* Angular
* Bootstrap 5


## 🚧 Future Enhancements

* 💳 Integrate Payment Gateway (**Razorpay / Stripe**)
* 🧠 Add **AI-based Product Recommendations**

---
