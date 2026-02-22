# Perfume Store Platform

A full-stack e-commerce application designed with layered backend architecture and RESTful API principles.

This project focuses on building scalable backend logic for product management, cart operations, authentication, and order processing.

---

##  Features

- RESTful APIs for products, categories, carts, and orders
- Layered architecture (Controller, Service, Repository)
- Relational database schema design (products, users, carts, orders)
- User authentication and authorization using Spring Security
- Shopping cart management (add/remove items, quantity updates, total calculation)
- Order checkout workflow with data persistence
- DTO mapping to separate entities from API responses
- Request validation and structured API responses
- Integration with React frontend via HTTP requests

---

##  Architecture

Backend follows a layered architecture pattern:

- Controller Layer – Handles HTTP requests
- Service Layer – Business logic and validation
- Repository Layer – Data access using JPA
- DTO mapping for clean API design

---

##  Tech Stack

Backend:
- Java 17
- Spring Boot
- Spring Security
- Spring Data JPA
- PostgreSQL
- Maven

Frontend:
- React
- HTML/CSS
- Fetch API

---

##  Key Backend Logic

- Product filtering and detailed retrieval
- Cart state management
- Order persistence workflow
- Exception handling and HTTP status management
