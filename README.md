# 🛒 E-commerce Website

An interactive and responsive e-commerce web application built to provide a smooth online shopping experience.  
This project demonstrates a complete online store system — including product listings, cart management, checkout, and user authentication.

---

## 🚀 Features

- 🏠 **Home Page** – Display featured and trending products  
- 🛍️ **Product Listing** – View all available products with categories and filters  
- 🔍 **Product Details** – Detailed view with images, description, and price  
- 🛒 **Shopping Cart** – Add, update, and remove products from the cart  
- 💳 **Checkout System** – Place orders and confirm purchases  
- 👤 **User Authentication** – Register, login, and logout functionality  
- ⚙️ **Admin Panel** – Manage products and view customer orders *(optional)*  
- ☁️ **AWS Cloud Integration** – Hosted and managed with AWS services  
- 📱 **Responsive Design** – Works on desktop, tablet, and mobile  

---

## 🧰 Technologies Used

| Category | Technology |
|-----------|-------------|
| Frontend | HTML, CSS, JavaScript, Bootstrap |
| Backend | Node.js / Express.js |
| Database | MongoDB / MySQL |
| Cloud Platform | **Amazon Web Services (AWS)** |
| AWS Services | **EC2**, **S3**, **Route 53** |
| Version Control | Git & GitHub |
| Tools | VS Code |

---

## ☁️ AWS Architecture Overview

### 🧩 **Amazon EC2 (Elastic Compute Cloud)**
- The backend server (Node.js + Express) is deployed on an **EC2 instance**.  
- The instance runs Ubuntu and serves the application through **Nginx** or **PM2** for process management.  
- SSH access is configured for deployment and monitoring.

### 🗂️ **Amazon S3 (Simple Storage Service)**
- Used for storing static assets such as product images, banners, and user uploads.  
- The frontend accesses S3 URLs directly for optimized image loading.  
- Versioning and public read policies are configured for security.

### 🌐 **Amazon Route 53**
- Handles domain registration and DNS routing for the e-commerce website.  
- The custom domain (e.g., `www.myonlinestore.com`) is linked to the EC2 public IP or load balancer.  
- Ensures high availability and fast global DNS resolution.

---
