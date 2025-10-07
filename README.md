# spring-boot-3-jwt-security

# 🔐 Spring Boot 3 + Spring Security 6 – JWT Authentication & Authorization

This project is a demo implementation of **JWT-based authentication and authorization** built with Spring Boot 3 and Spring Security 6.  
It follows the 2023 tutorial *"Spring Boot 3 + Spring Security 6 - JWT Authentication and Authorization"* and demonstrates modern best practices for securing REST APIs.

---

## 🚀 Features
- User registration and login
- Password hashing with `BCryptPasswordEncoder`
- JWT (JSON Web Token) generation & validation
- Authentication filter (`OncePerRequestFilter`)
- Role-based authorization
- Stateless security configuration with Spring Security 6
- PostgreSQL integration with Spring Data JPA

---

## 🛠️ Tech Stack
- **Java 17**
- **Spring Boot 3**
- **Spring Security 6**
- **Spring Data JPA**
- **PostgreSQL**
- **Lombok**
- **JSON Web Token (jjwt 0.12.x)**

---

## 📂 Project Structure
├── auth

│ ├── AuthenticationController.java

│ ├── AuthenticationService.java

│ ├── AuthenticationRequest.java

│ ├── AuthenticationResponse.java

│ └── RegisterRequest.java

├── config

│ ├── ApplicationConfig.java

│ ├── JwtAuthenticationFilter.java

│ ├── JwtService.java

│ └── SecurityConfiguration.java

├── demo

│ ├── DemoController.java

├── user

│ ├── User.java

│ ├── Role.java

└── UserRepository.java

└── SecurityApplication.java
