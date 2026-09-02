<div align="center">
  <h1>☕ Spring Boot Architecture & Microservices Forge</h1>
  <h3>Enterprise Backend Systems, API Design, and System Architecture</h3>
  
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white" alt="Maven" />
  <img src="https://img.shields.io/badge/Security-JWT-blue?style=for-the-badge" alt="JWT Security" />
</div>

---

## 📌 The Vision

This repository represents my rigorous progression through enterprise-grade backend development. It serves as a comprehensive vault of Maven-based Spring Boot applications, demonstrating my ability to architect robust APIs, transition from monolithic systems to microservices, and implement bulletproof security layers.

Designed with industry standards in mind, this codebase highlights my technical bridge between complex data processing and seamless client-side consumption.

## 🏛️ Architectural Highlights

The projects are categorized by architectural focus, showcasing a broad spectrum of backend capabilities:

### 1. E-Commerce Ecosystem (Monolith to Microservices)
A complete transition from a unified architecture to distributed services.
* **`Monolithic e-commerce application`** - The baseline architecture handling all domains in a single instance.
* **Microservices Breakdown:** Scalable, independent services encompassing **`order`**, **`product`**, and **`Category`** domains.
* **`e-Commerce Website SpringBoot` & `e-Commerce Website - dashboard.jsx`** - The integration layer, demonstrating how the Spring Boot backend directly interfaces with a modern React front-end dashboard for a full-stack flow.

### 2. Enterprise Security & Authentication
* **`JWT-DEMO` & `JWT-DEMO Improved`** - Implementation of JSON Web Tokens (JWT) for stateless, secure user authentication and authorization.
* **`security`** - Core Spring Security configurations mapping roles, authorities, and filter chains.

### 3. System Design & Configurations
* **`LLD_01` & `SDP`** - Low-Level Design and Software Design Pattern implementations, proving a focus on scalable and maintainable code structure over quick fixes.
* **`Profile in Spring Boot`** - Environment management (Dev, Test, Prod) demonstrating deployment-readiness.

## ⚙️ The Engine (How to Run)

All backend modules are strictly **Maven-based**. To run any of these services locally:

1. **Extract the target module:** Unzip your chosen microservice or monolithic application.
2. **Navigate into the project root:**
   ```bash
   cd extracted-folder-name
