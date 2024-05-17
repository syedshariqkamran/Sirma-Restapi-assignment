# Sirma-Restapi-assignment
Prerequisites
Before running this application, ensure you have the following:

Java 17 installed on your machine
Familiarity with Spring Boot framework
Basic understanding of RESTful API principles
Knowledge of in-memory databases (H2 Database used in this project)

Database Configuration
Configure the H2 in-memory database in application.properties.
Define the schema for the 'Student' entity with attributes like id, name, gender, city, etc.
Model Creation
Create a Student model class in the beans package with annotations for JPA entity.

Repository Layer
Create a StudentDao interface extending JpaRepository to handle data operations.

Service Layer
Implement a StudentService interface and a corresponding StudentServiceImpl class to handle business logic and define methods for create, read, update, and delete operations.

Controller Layer
Develop a MyController class in the controllers package to handle HTTP requests and map CRUD operations to RESTful endpoints (e.g., POST /student, GET /student, PUT /student, DELETE /student/{id}, etc.).
