# Student CRUD Operations - Spring Boot Application

This is a Spring Boot application that demonstrates basic CRUD (Create, Read, Update, Delete) operations for managing student information. The application uses Spring Data JPA to interact with the database and exposes a set of RESTful APIs for performing operations on student data.

## Features
- Create a new student
- Retrieve a list of all students
- Retrieve a student by ID
- Update student information
- Delete a student

## Technologies Used
- **Java 8+**: The main programming language.
- **Spring Boot**: A framework for building Java applications.
- **Spring Data JPA**: For ORM (Object-Relational Mapping) and database access.
- **MySQL**: Relational Database for data persistence.
- **Hibernate**: JPA implementation for managing database operations.
- **Spring Web**: To expose RESTful services.
- **Maven**: Dependency management and project build tool.

## Prerequisites
- **Java**: 8 or higher version should be installed.
- **Maven**: Ensure that Maven is installed to manage dependencies and build the project.
- **MySQL**: Setup a MySQL database for the application.

## API Endpoints
Once the application is up and running, the following RESTful endpoints are available:

- **GET /api/students**: Retrieve all students.
- **GET /api/students/{id}**: Retrieve a specific student by ID.
- **POST /api/students**: Create a new student. The request body must contain the student details in JSON format.
- **PUT /api/students/{id}**: Update an existing student by ID.
- **DELETE /api/students/{id}**: Delete a student by ID.

## Support
If you encounter any issues or have any questions, please feel free to contact us at diksharaut2511@gmail.com
