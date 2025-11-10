# 🧩 System Architecture Documentation

## 🎯 Objective
Design a modular, full-stack e-commerce application that allows users to browse, view, and manage products and a shopping cart efficiently.

---

## 🏗️ Architecture Overview

**Frontend:** React.js (Vite)  
**Backend:** Spring Boot (Java)  
**Database:** MySQL  

### 🔹 Component Layers
| Layer | Technology | Description |
|--------|-------------|-------------|
| Presentation | React.js | UI components (Home, Product, Cart, Navbar) |
| Application | Spring Boot | REST APIs to manage products |
| Persistence | JPA + MySQL | Stores products and cart info |

---

### 🔹 Data Flow Diagram
[React Frontend] → [Axios API Calls] → [Spring Boot Controller] → [Service Layer] → [JPA Repository] → [MySQL Database]


---

### 🔹 REST Endpoints
| Method | Endpoint | Description |
|---------|-----------|-------------|
| GET | `/api/products` | Fetch all products |
| POST | `/api/products` | Add new product |
| PUT | `/api/products/{id}` | Update product |
| DELETE | `/api/products/{id}` | Delete product |

---

### 🔹 Deployment Notes
- Frontend: React served with Vite  
- Backend: Spring Boot `8080`  
- Database: MySQL local instance (`ecom_db`)  

---

**Author:** Vishwa R  
**Created For:** Diligent Internship Assessment 2025
