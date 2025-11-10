# 🛍️ Vishwa E-Commerce App

**A full-stack mini e-commerce web app built with React, Spring Boot, and MySQL**  
Developed for the **Diligent Internship Assessment (2025)** in under 20 minutes ⚡

---

## 🚀 Features
- 🧭 Browse products from a dynamic MySQL database  
- 🪄 View detailed product information  
- 🛒 Add/remove products to a shopping cart (React state-managed)  
- 🌐 REST API backend (Spring Boot + JPA)  
- 💾 MySQL integration with auto schema updates  
- 📱 Responsive UI

---

## 🧠 Tech Stack
| Layer | Technology |
|-------|-------------|
| Frontend | React.js (Vite) |
| Backend | Java Spring Boot |
| Database | MySQL |
| Build Tools | Maven |
| IDEs Used | IntelliJ IDEA & VS Code |

---

## 🏗️ Architecture Overview
**Frontend** → React Components + Context API  
**Backend** → REST API Controllers → Service Layer → Repository (JPA) → MySQL  

```plaintext
React App → REST API → Spring Service → JPA → MySQL

🧩 Database Schema

Table: product

Column	Type	Description
id	INT (PK)	Auto-generated
name	VARCHAR	Product name
description	TEXT	Product description
price	DOUBLE	Product price
imageUrl	VARCHAR	Image path


⚙️ Run Instructions
🖥️ Backend
cd ecom-backend
mvn spring-boot:run


Visit: http://localhost:8080/api/products

🌐 Frontend
cd ecom-frontend
npm install
npm run dev


Visit: http://localhost:5173
