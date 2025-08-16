# Spring Boot Security & JWT Project

## Project Overview
This repository contains a Spring Boot 3 application developed as part of the Udemy course *"Spring Boot 3 and Spring Framework 6"* by Shabbir Dawoodi. The project focuses on implementing **Spring Security** (Section 11) and **Spring Security with JSON Web Tokens (JWT)** (Section 12) to secure a RESTful API. The goal was to learn how to protect endpoints, manage user authentication and authorization, and integrate JWT for stateless authentication.

### Key Features
- **Spring Security (Section 11)**:
    - Configured Spring Security to protect REST API endpoints.
    - Implemented user authentication using in-memory and database-backed user details.
    - Applied role-based authorization to restrict access to specific endpoints.
    - Configured security filters for handling authentication and authorization.
    - Demonstrated password encoding using BCrypt.
- **Spring Security with JWT (Section 12)**:
    - Integrated JSON Web Tokens (JWT) for stateless authentication.
    - Implemented token generation and validation for secure API access.
    - Configured a custom JWT authentication filter.
    - Secured endpoints using JWT-based authentication and authorization.

## Technologies Used
- **Java**: 17
- **Spring Boot**: 3.x
- **Spring Security**: 6.x
- **JSON Web Tokens (JWT)**: For stateless authentication
- **Maven**: Dependency management
- **Postman**: For testing API endpoints