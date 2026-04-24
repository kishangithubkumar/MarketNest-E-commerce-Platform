# 🛒 MarketNest – E-commerce Backend Platform

## 🚀 Overview

**MarketNest** is a **production-grade e-commerce backend system** built using **Spring Boot**, designed to handle real-world online shopping operations including authentication, product management, cart workflows, and order processing.

The project emphasizes:

* Scalable backend architecture
* Secure authentication using JWT
* API documentation with Swagger
* Containerized deployment using Docker

---

## 🏗️ Architecture
<img width="1536" height="1024" alt="ChatGPT Image Apr 25, 2026, 01_21_10 AM" src="https://github.com/user-attachments/assets/ffdd3b34-83f8-4b04-8ad5-9ec0df80ad22" />

## ER-Diagram
<img width="1165" height="1631" alt="ecommerce-er-diagram (1)_page-0001" src="https://github.com/user-attachments/assets/e1a01942-7ac4-4d86-a2f1-4953a704414b" />


The system follows a **layered architecture pattern** ensuring modularity and maintainability:

* **Controller Layer** → Handles API requests
* **Service Layer** → Business logic
* **Repository Layer** → Database interaction
* **DTO Layer** → Data transfer abstraction
* **Security Layer** → JWT-based authentication

---

## ⚙️ Tech Stack

| Category   | Technology           |
| ---------- | -------------------- |
| Backend    | Java, Spring Boot    |
| Security   | Spring Security, JWT |
| Database   | MySQL / PostgreSQL   |
| ORM        | Spring Data JPA      |
| API Docs   | Swagger (OpenAPI)    |
| Container  | Docker               |
| Build Tool | Maven                |

---

## 📂 Project Structure

```id="u0n5h9"
com.ecommerce.project
│
├── controller
├── service
├── repository
├── model
├── dto
├── security
├── exception
├── config
└── util
```

---

## 🔐 Authentication & Authorization

* JWT-based authentication
* Role-based access control
* Secure API endpoints
* Stateless session management

---

## 📦 Core Features

### 🛍️ Product & Category Management

* Create, update, delete products
* Search, pagination & sorting

### 🛒 Cart Management

* Add/remove products
* Update quantity
* Fetch user cart

### 📑 Order Management

* Place orders
* Convert cart → order
* Order tracking

### 👤 User & Role Management

* User registration
* Role assignment
* Profile management

### 📍 Address Management

* Add/update addresses
* Fetch user addresses

---

## 📄 API Documentation (Swagger)

Interactive API documentation is available via Swagger UI:

```id="q0y9s7"
http://localhost:8080/swagger-ui/index.html
```

Features:

* Test APIs directly from browser
* View request/response models
* JWT authentication support

---

## 🐳 Docker Support

The application is fully containerized for consistent deployment.

### Build Docker Image

```bash id="5s8pjz"
docker build -t marketnest-backend .
```

### Run Container

```bash id="xg0a8c"
docker run -p 8080:8080 marketnest-backend
```

---


### 1️⃣ Clone Repository

```bash id="2n5b0j"
git clone https://github.com/kishangithubkumar/MarketNest-E-commerce-Platform.git
cd MarketNest-E-commerce-Platform
```

---

### 2️⃣ Configure Database

```properties id="6gk7wx"
spring.datasource.url=jdbc:mysql://localhost:3306/marketnest
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
```

---

### 3️⃣ Run Application

```bash id="6lp4sj"
mvn spring-boot:run
```

---

### 4️⃣ Access Services

* Swagger UI → http://localhost:8080/swagger-ui/index.html
* API Base URL → http://localhost:8080

---

## 📊 Key Highlights

✔️ Production-style backend system
✔️ JWT-based secure authentication
✔️ Full e-commerce business logic
✔️ Swagger API documentation
✔️ Dockerized deployment
✔️ Clean layered architecture

---

## 🧠 Engineering Concepts Used

* DTO Pattern
* Exception Handling
* Validation (`@Valid`)
* JPA Relationships
* Stateless Authentication (JWT)
* Pagination & Sorting

---

## 🎯 Future Enhancements

* Payment gateway integration
* API Gateway implementation
* Microservices migration
* CI/CD pipeline (GitHub Actions)
* Kubernetes deployment

---

## 👨‍💻 Author

**Kishan Kumar**
GitHub: https://github.com/kishangithubkumar

---

## ⭐ Support

If you found this project useful, give it a ⭐ on GitHub!
