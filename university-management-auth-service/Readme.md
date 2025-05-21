# 🔐 University Management System – Authentication Service

### 👨‍💻 Built & Maintained by Norul Islam (Jewel)

This is the **Authentication Service** of the University Management System – a complete role-based access control (RBAC) solution built by me using modern technologies like **TypeScript**, **Express.js**, **Zod**, and **MongoDB**.

It handles login, profile management, and role-based authorization for:

- 🧑‍🎓 Students
- 👨‍🏫 Faculties
- 👨‍💼 Admins

---

## 🧰 Core Features

### ✅ Authentication & Session

- Login/logout
- Password change
- Refresh tokens

  ### 🧑‍🎓 Student Functions

- Login/logout
- Profile management (partial updates)

### 👨‍🏫 Faculty Functions

- Login/logout
- Profile management (restricted updates)

### 👨‍💼 Admin Functions

- Full user management
- Change passwords
- Role-based access control
- Admin profile updates (restricted fields)

---

## 🧪 API Endpoints (Grouped by Feature)

### User

- `POST /users/create-student`
- `POST /users/create-faculty`
- `POST /users/create-admin`

### Student

- `GET /students`
- `GET /students?searchTerm=fr797`
- `GET /students?page=1&limit=10&sortBy=gender&sortOrder=asc`
- `GET /students/:id`
- `PATCH /students/:id`
- `DELETE /students/:id`

### Faculty

- `GET /faculties`
- `GET /faculties?searchTerm=john`
- `GET /faculties?page=1&limit=10&sortBy=gender&sortOrder=asc`
- `GET /faculties/:id`
- `PATCH /faculties/:id`
- `DELETE /faculties/:id`

### Admin

- `GET /admins`
- `GET /admins?searchTerm=us88`
- `GET /admins?page=1&limit=10&sortBy=gender&sortOrder=asc`
- `GET /admins/:id`
- `PATCH /admins/:id`
- `DELETE /admins/:id`

### Academic Semester

- `POST /academic-semesters/create-semester`
- `GET /academic-semesters`
- `GET /academic-semesters?searchTerm=fal`
- `GET /academic-semesters?page=1&limit=10&sortBy=year&sortOrder=asc`
- `GET /academic-semesters/:id`
- `PATCH /academic-semesters/:id`
- `DELETE /academic-semesters/:id`

### Academic Department

- `POST /academic-departments/create-department`
- `GET /academic-departments`
- `GET /academic-departments?searchTerm=math`
- `GET /academic-departments?page=1&limit=10&sortBy=title&sortOrder=asc`
- `GET /academic-departments/:id`
- `PATCH /academic-departments/:id`
- `DELETE /academic-departments/:id`

### Academic Faculty

- `POST /academic-faculties/create-faculty`
- `GET /academic-faculties`
- `GET /academic-faculties?searchTerm=com`
- `GET /academic-faculties?page=1&limit=10&sortBy=title&sortOrder=asc`
- `GET /academic-faculties/:id`
- `PATCH /academic-faculties/:id`
- `DELETE /academic-faculties/:id`

### Authentication

- `POST /auth/login`
- `POST /auth/change-password`
- `POST /auth/refresh-token`

---

## 📄 API Documentation

🔗 [View Full Postman Docs](https://documenter.getpostman.com/view/26682150/2s93zB72V9#acc25f08-de78-478b-809d-837ce239d2b3)

---

## 👤 Author

**Norul Islam (Jewel)**
