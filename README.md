# College Library Management System

## Description

A web application to manage library information using Java, JDBC, Servlets, and JSP.

## Features

1. Student Registration
2. Book Management: Add, update, delete, and search books
3. Book borrowing with fine calculation
4. Limit on the number of books borrowed by students
5. Book search by author, title, and category
6. Librarian registration and book issuance

## Technologies

- Java
- JDBC
- Servlet
- JSP
- MySQL
- HTML
- CSS

## Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/CollegeLibraryManagement.git
    ```

2. Set up the MySQL database using the provided schema.

3. Configure the database connection in `DatabaseConnection.java`.

4. Deploy the project on a servlet container (e.g., Apache Tomcat).

5. Access the application at `http://localhost:8080/CollegeLibraryManagement`.

## System Design

### High-Level Design (HLD)

- The application consists of a frontend (JSP) and a backend (Servlets and JDBC).
- MySQL is used as the database to store student, book, and borrowing information.

### Low-Level Design (LLD)

- Detailed implementation of each module, including database connection, servlets for handling requests, and JSP pages for the user interface.

## System Architecture

- Client-Server architecture
- Modular design for maintainability and scalability

## Test Cases

- Student registration with valid and invalid data
- Book management operations (add, update, delete, search)
- Borrowing books and calculating fines

## Deployment

- The application can be deployed locally using a servlet container or on a cloud platform.
- Justify the chosen deployment strategy based on the project's requirements.

## Optimization

- Code-level: Efficient database queries, proper error handling
- Architecture-level: Separation of concerns, modular design


