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
# Code
```java
public class Main {
  public static void main(String args[]){
    System.out.println("Welcome to the world of Java...");
  }
}
```
# Tables

| Sr. | Country | Capital |
|-----|---------|---------|
| 1   | India   | Delhi   |
| 2   | USA     | Washington |
| 3   | Russia  | Moscow |
| 4   | China   | Beijing |

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
# New Project Structure
```
test/
├── controller/
│   └── EmployeeController.java
├── Git and GitHub.txt
├── HelloWorld.java
├── index.html
├── README.md
├── Springboot.txt
├── Test.txt
├── Test1.txt
└── Welcome.java
```
![Maven](https://img.shields.io/badge/Maven-3.9-blue)
![Java](https://img.shields.io/badge/Java-17-orange)
![Spring Boot](https://img.shields.io/badge/SpringBoot-3.x-brightgreen)
