# Springboot CRUD Employee Management

## Description

The **Springboot CRUD Employee Management** project is a web-based application that allows users to manage employee data efficiently. It provides basic CRUD (Create, Read, Update, Delete) operations, showcasing the capabilities of Spring Boot, Spring MVC, JPA, and Thymeleaf for developing a robust, scalable, and user-friendly application.

---

## Features

- **Add New Employee**: Create and add new employee records to the system.
- **View Employee Details**: Retrieve and display the list of all employees, including their details.
- **Update Employee Information**: Edit existing employee data seamlessly.
- **Delete Employee**: Remove employee records from the system.
- **Search Functionality**: Quickly find employees based on specific criteria.

---

## Technologies Used

- **Backend**:  
  - Spring Boot (Core Framework)
  - Spring Data JPA (Database Access Layer)
  - Hibernate (ORM Tool)

- **Frontend**:  
  - Thymeleaf (HTML Templates)
  - CSS (Styling)

- **Database**:  
  - MySQL (Relational Database)

- **Tools and Environment**:  
  - IntelliJ IDEA / Eclipse (IDE)
  - Maven (Dependency Management)
  - Postman (API Testing)
  - GitHub (Version Control)

---

## Prerequisites

- JDK 11 or above
- Maven 3.6+
- MySQL Database
- IDE (e.g., IntelliJ IDEA, Eclipse)
- Git

---

## Setup and Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Abhijeet0112/Springboot_CRUD_Emp_Management.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Springboot_CRUD_Emp_Management
   ```

3. Configure the database in the `application.properties` file:

   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/your_database_name
   spring.datasource.username=your_username
   spring.datasource.password=your_password
   spring.jpa.hibernate.ddl-auto=update
   ```

4. Build the project using Maven:

   ```bash
   mvn clean install
   ```

5. Run the Spring Boot application:

   ```bash
   mvn spring-boot:run
   ```

6. Open your browser and access the application at:

   ```
   http://localhost:8080
   ```

---

## Project Structure

```plaintext
Springboot_CRUD_Emp_Management/
├── src/main/java/com/example/employee
│   ├── controller/         # Contains all REST controllers
│   ├── model/              # Defines the Employee entity
│   ├── repository/         # Contains JPA repositories
│   ├── service/            # Business logic services
│   └── SpringbootCrudEmpManagementApplication.java  # Main class
├── src/main/resources
│   ├── templates/          # Thymeleaf templates (HTML files)
│   ├── static/             # Static files (CSS, JS)
│   └── application.properties  # Application configuration
└── pom.xml                 # Maven dependencies and build configuration
```

---

## API Endpoints

| Method | Endpoint                 | Description                        |
|--------|---------------------------|------------------------------------|
| GET    | `/employees`             | View all employees                |
| GET    | `/employees/{id}`        | Get employee details by ID        |
| POST   | `/employees`             | Add a new employee                |
| PUT    | `/employees/{id}`        | Update an existing employee       |
| DELETE | `/employees/{id}`        | Delete an employee by ID          |

---

## Screenshots

*Include relevant screenshots here to demonstrate the UI of the application.*

---

## Contributions

Contributions are welcome! If you'd like to contribute, feel free to submit a pull request or create an issue.

---
