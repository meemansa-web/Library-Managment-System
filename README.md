# 📚 Library Management System

A robust Library Management System developed using **Spring Boot** and **Spring Data JPA** to streamline the management of books, students, and borrowing transactions. The system ensures efficient data handling, reduces manual effort, and demonstrates real-world backend development practices.

## 🚀 Key Features
- CRUD operations for books and student records  
- Book issuing and return management  
- Centralized record tracking and organization  
- Search functionality for quick data retrieval  
- Clean layered architecture (Controller–Service–Repository)

## 🛠️ Tech Stack
- **Backend:** Java, Spring Boot  
- **Database:** MySQL  
- **ORM:** Spring Data JPA (Hibernate)  
- **Tools:** Postman, Maven  

## 📂 Project Architecture
- `controller` – REST API endpoints  
- `service` – Business logic layer  
- `repository` – Data access layer using JPA  
- `entity/model` – Domain models mapped to database  

## ⚙️ Setup & Execution
1. Clone the repository  
2. Configure database credentials in `application.properties`  
3. Build and run the application using Maven or IDE  
4. Test APIs via Postman or any REST client  

## 🔗 API Endpoints

### 📘 Book Management
- `GET /books` – Retrieve all books  
- `GET /books/{id}` – Retrieve book by ID  
- `POST /books` – Create a new book  
- `PUT /books/{id}` – Update book details  
- `DELETE /books/{id}` – Remove a book  

### 👨‍🎓 Student Management
- `GET /students` – Retrieve all students  
- `GET /students/{id}` – Retrieve student by ID  
- `POST /students` – Register a new student  
- `PUT /students/{id}` – Update student details  
- `DELETE /students/{id}` – Delete a student  

### 🔄 Transaction Management
- `POST /issue` – Issue a book to a student  
- `POST /return` – Process book return  

## 🎯 Objective
This project demonstrates the implementation of a scalable backend system using Spring Boot and JPA, focusing on clean architecture, RESTful API design, and database integration.
