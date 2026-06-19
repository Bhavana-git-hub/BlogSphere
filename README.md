# BlogSphere - Blog Management Platform

## Overview

BlogSphere is a full-stack blog management platform developed using Spring Boot. The application allows users to create, manage, and interact with blog posts through a secure and user-friendly interface. It implements Role-Based Access Control (RBAC) and JWT Authentication to ensure secure access to resources.

## Features

### User Management

* User Registration
* User Login
* JWT Authentication
* Role-Based Authorization (Admin/User)

### Blog Management

* Create Blog Posts
* Update Blog Posts
* Delete Blog Posts
* View All Posts
* View Single Post

### Comment System

* Add Comments to Posts
* View Comments
* Manage User Interactions

### Category Management

* Create Categories
* Assign Categories to Posts
* Filter Posts by Category

### Security

* Spring Security Integration
* JWT Token Authentication
* Role-Based Access Control

## Technology Stack

### Backend

* Java 21
* Spring Boot
* Spring Security
* Spring Data JPA
* Hibernate

### Database

* MySQL

### Tools

* Maven
* Postman
* Git & GitHub

## Project Structure

* Authentication Module
* User Management Module
* Blog Post Module
* Comment Module
* Category Module
* Security Module

## Database Configuration

Update the `application.properties` file:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/blogsphere
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

## How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/blogsphere.git
```

2. Open the project in IntelliJ IDEA or VS Code

3. Configure MySQL Database

4. Run the application

```bash
mvn spring-boot:run
```

5. Access the application

```text
http://localhost:8080
```

## REST API Modules

* Authentication API
* User API
* Blog Post API
* Comment API
* Category API

## Learning Outcomes

This project demonstrates:

* RESTful API Development
* Spring Boot Architecture
* JWT Authentication
* Role-Based Security
* Database Integration
* CRUD Operations
* Content Management Systems

## Future Enhancements

* Image Upload Support
* Rich Text Editor
* Email Notifications
* Search Functionality
* Likes and Reactions
* Pagination and Sorting

## Author

**PALAVALASA BHAVANA**

B V Raju Institute of Technology (BVRIT)

GitHub:https://github.com/Bhavana-git-hub 

---

Developed as a Full-Stack Blog Management Platform using Spring Boot and MySQL.
