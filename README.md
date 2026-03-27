# Springboot application layers
1. Controller layer
2. Service layer
3. Repository/DAO layer

# Project Folder structure
```
E-commerce
└── src/main/java
    ├── com.nt.controller
    │   ├── UserController.java
    │   └── ProductController.java
    ├── com.nt.service
    │   ├── UserService.java
    │   └── ProductService.java
    └── com.nt.repository
        ├── UserRepository.java
        └── ProductRepository.java
```

# Project Flow Diagram
```mermaid
sequenceDiagram
    participant User
    participant Frontend
    participant Backend
    participant Database

    User->>Frontend: Login Request
    Frontend->>Backend: API Call (/login)
    Backend->>Database: Validate User
    Database-->>Backend: User Data
    Backend-->>Frontend: JWT Token
    Frontend-->>User: Login Success
```
