# 🎓 University Management API Gateway

### 👨‍💻 Architected & Developed by Norul Islam (Jewel)

This is the **central gateway service** for my University Management System.  
I built this project independently as part of a complete microservices architecture. It handles request routing, authentication, file uploads, and secure proxying between backend services.

---

## 📌 Overview

The API Gateway serves as the unified entry point for all microservices in the system.  
It handles:

- Request routing to **Auth Service** (`um-auth`)
- Request routing to **Core Service** (`um-core`)
- Secure middleware for token validation
- Centralized media upload and delivery flow

---

## 🚀 Key Contributions

✅ Designed scalable folder structure with **modular Express.js**  
✅ Implemented **proxy routing** with dynamic endpoint mapping  
✅ Added **Redis** for token/session caching  
✅ Used **Multer** for file uploads  
✅ Connected **Cloudinary** for cloud image storage

---

## 🛠️ Tech Stack

- **Node.js**
- **Express.js**
- **Redis**
- **Multer**
- **Cloudinary**
- **TypeScript** (optional, if used)

---

## 🧠 Purpose

This gateway was built to:

- Centralize control over distributed services
- Handle auth and media functions at the edge layer
- Improve scalability and maintainability
- Demonstrate system design skills with real-world microservices

---

## 📄 API Documentation

🔗 [Postman Docs](https://documenter.getpostman.com/view/26694209/2s9YC5zCgD)

---

## 📥 Getting Started

```bash
git clone https://github.com/NORULISLAM/university-management-api-gateway.git
cd university-management-api-gateway
npm install
npm run dev
```
