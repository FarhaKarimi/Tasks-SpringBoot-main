
Spring Boot To-Do List App
A simple To-Do List application built with Spring Boot, Thymeleaf, and Spring Security. This app allows users to create, read, update, and delete tasks. It also supports user registration and secure login.

Features
CRUD Operations: Create, read, update, and delete tasks.

User Registration: New users can sign up and create accounts.

User Authentication: Secure login using Spring Security.

Password Hashing: Passwords are securely hashed before storing.

Thymeleaf Templates: Frontend views rendered with Thymeleaf.

Technologies Used
Spring Boot: Framework for building standalone production-ready Spring applications.

Thymeleaf: Server-side Java template engine for rendering views.

Spring Security: Authentication and access control framework.

Spring Data JPA: Simplifies data access using JPA.

Hibernate: Object-relational mapping tool.

PostgreSQL / H2 Database: Choose your preferred relational database.

Getting Started
Prerequisites
Java JDK 8 or higher

Maven

Your preferred IDE (IntelliJ IDEA, Eclipse, etc.)

PostgreSQL or H2 database installed and running

Installation
Clone the repository:

bash
Copy
Edit
git clone <repository-url>
Navigate to the project directory:

bash
Copy
Edit
cd todo-list-app
Update application.properties with your database configuration:

properties
Copy
Edit
spring.datasource.url=jdbc:postgresql://localhost:5432/db_todolist
spring.datasource.username=postgres
spring.datasource.password=root
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.PostgreSQLDialect
spring.jpa.hibernate.ddl-auto=update
Build the project:

bash
Copy
Edit
mvn clean package
Run the application:

bash
Copy
Edit
mvn spring-boot:run
Open your browser and visit http://localhost:8080 to access the app.

Usage
Create an Account: Click the "Sign Up" link to register.

Login: After registering, log in with your credentials.

Manage Tasks: Add, edit, or delete your to-do tasks.
