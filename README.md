# **Java Master class**

## **Course Overview**

This 12-week course introduces students to Java for backend development, emphasizing **essential language concepts**, **database access with JPA**, and building **RESTful APIs** using **Spring Boot**. By the end, students will be able to design, implement, and deploy a basic, full-featured backend service.

For the final project, students will integrate all their learnings to build a **Book Management System** with authentication, database integration, and deployment on a cloud platform.

---

## **Week 1: Java Basics & OOP**

- Java Overview and Setup (JDK, IDE)
- Basic Syntax (Variables, Data Types, Operators)
- Control Structures (If-else, Switch, Loops)
- Object-Oriented Programming (Classes, Objects, Methods)
- Core OOP Principles: Encapsulation, Inheritance, Polymorphism, Abstraction

### **Week 1 Task**

Create a simple Java program that demonstrates basic OOP principles (e.g., a small library system with books and authors).

---

## **Week 2: Java Collections & Data Structures**

- Arrays and Strings
- Java Collections (List, Set, Map)
- Common Implementations (ArrayList, LinkedList, HashMap, HashSet)
- Iterating over Collections (For, For-each)

### **Week 2 Task**

Develop a program to manage a list of students using Java Collections, allowing basic CRUD operations.

---

## **Week 3: Exception Handling & File I/O**

- Exception Handling (try-catch, throw, throws)
- Writing Custom Exceptions
- File Handling Basics (Reading/Writing Files)
- Intro to Serialization & Deserialization

### **Week 3 Task**

Create a program that reads student data from a file, processes it (e.g., adds grades), and writes the output to another file.

---

## **Week 4: Databases & JPA Basics**

- Overview of Relational Databases
- Introduction to JPA (Java Persistence API)
- Entity-Relationship Mapping
- Setting up Database Connections and Basic Entity Classes

### **Week 4 Task**

Build a simple Java console app to map entities to a database table using JPA (e.g., a `Student` entity stored in a database).

---

## **Week 5: CRUD Operations with JPA**

- Defining JPA Entities (@Entity, @Table, @Id)
- CRUD Operations (Create, Read, Update, Delete)
- Mapping Relationships (One-to-Many, Many-to-One)

### **Week 5 Task**

Expand the previous app to include CRUD operations for managing database entities (e.g., adding, updating, or removing students).

---

## **Week 6: Maven & Project Setup**

- Maven Basics (POM, Dependencies)
- Building and Packaging Projects with Maven
- Setting up a Basic Spring Boot Project with Maven

### **Week 6 Task**

Set up a Maven-based Spring Boot project, adding dependencies for JPA and testing its functionality.

---

## **Week 7: Introduction to Spring Boot**

- Overview of Spring Framework and Spring Boot
- Spring Boot Basics (@SpringBootApplication)
- Understanding Dependency Injection
- Creating a Simple Spring Boot Application

### **Week 7 Task**

Build a Spring Boot app with basic dependency injection and a simple REST controller.

---

## **Week 8: Building REST APIs with Spring Boot**

- RESTful Web Services Overview
- Building REST Controllers (@RestController, @RequestMapping)
- Handling HTTP Methods (GET, POST, PUT, DELETE)
- Validating Requests with @Valid

### **Week 8 Task**

Create a REST API for managing a simple resource like "Products" or "Books."

---

## **Week 9: Spring Data JPA & Database Integration**

- Connecting Spring Boot with Databases
- Spring Data JPA Overview (Repositories)
- Query Methods and Custom Queries
- Implementing Database CRUD via REST

### **Week 9 Task**

Integrate a database with the REST API and add CRUD functionality for the resource managed in Week 8.

---

## **Week 10: Security, Testing, & Deployment**

- Spring Security Overview (Authentication & Authorization)
- Securing APIs with JWT (JSON Web Tokens)
- Testing REST APIs (JUnit, MockMvc)
- Deploying Spring Boot Applications (e.g., Heroku, AWS)

### **Week 10 Task**

Secure the REST API with Spring Security and JWT, then deploy it to a cloud platform.

---

## **Weeks 11-12: Final Project**

### **Project: Book Management System**

Students will develop a **Book Management System** with the following features:

1. **User Authentication**:
    - User registration and login using Spring Security and JWT.
    - API endpoints secured for authenticated users.
2. **Book Management API**:
    - CRUD endpoints for managing books (`title`, `author`, `isbn`, `publishedDate`, `genre`).
    - Features like pagination and filtering.
3. **Database Integration**:
    - Use Spring Data JPA for database operations.
    - Establish user-to-book relationships.
4. **Validation**:
    - Validate input (e.g., required fields, valid ISBN).
5. **Testing**:
    - Unit and integration tests for endpoints.
6. **Deployment**:
    - Deploy the app on a cloud platform with production settings.

---
