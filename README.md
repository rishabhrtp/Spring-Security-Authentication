# Spring Security Authentication

A Spring Boot authentication project that implements user registration, login, Spring Security, MySQL database integration, and Google OAuth2 authentication.

## Features

- User Registration
- User Login with Email and Password
- Password Encryption using BCrypt
- Spring Security Authentication
- Role-based User Management
- Google OAuth2 Login
- Automatic Google User Registration in MySQL
- Logout
- MySQL Database Integration
- Thymeleaf UI
- HTML & CSS based Login and Registration Pages

## Tech Stack

- Java 25
- Spring Boot 4.1.1
- Spring Security
- Spring Data JPA
- OAuth2 Client
- Hibernate
- MySQL
- Thymeleaf
- HTML
- CSS
- Maven

## Project Structure

```text
src
└── main
    ├── java
    │   └── com.rishabh.spring_security_auth
    │       ├── controller
    │       │   └── AuthController.java
    │       │
    │       ├── entity
    │       │   └── User.java
    │       │
    │       ├── repository
    │       │   └── UserRepository.java
    │       │
    │       ├── service
    │       │   └── UserService.java
    │       │
    │       └── security
    │           ├── SecurityConfig.java
    │           ├── CustomUserDetailsService.java
    │           └── CustomOAuth2UserService.java
    │
    └── resources
        ├── static
        │   └── css
        │       └── style.css
        │
        ├── templates
        │   ├── home.html
        │   ├── login.html
        │   ├── register.html
        │   └── dashboard.html
        │
        └── application.properties
