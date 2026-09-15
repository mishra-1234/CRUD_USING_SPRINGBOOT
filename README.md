# CRUD Using Spring Boot

A simple **CRUD (Create, Read, Update, Delete) web application** built using **Java and Spring Boot**.
This project demonstrates how to create REST APIs and perform database operations using Spring Boot.

## 🚀 Features

* Create a new student record
* Get all student records
* Get a student by ID
* Update student details
* Delete a student record
* RESTful API architecture
* Database integration using Spring Data JPA

## 🛠️ Technologies Used

* **Java**
* **Spring Boot**
* **Spring Data JPA**
* **REST API**
* **MySQL**
* **Maven**
* **IntelliJ IDEA**
* **Postman** for API testing

## 📂 Project Structure

```text
CRUD-SPRINGBOOT/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com.example.CRUD_SPRINGBOOT/
│   │   │       ├── controller/
│   │   │       ├── entity/
│   │   │       ├── repository/
│   │   │       └── service/
│   │   │
│   │   └── resources/
│   │       └── application.properties
│   │
│   └── test/
│
├── pom.xml
├── mvnw
├── mvnw.cmd
└── .gitignore
```

## ⚙️ Setup & Installation

### 1. Clone the repository

```bash
git clone https://github.com/mishra-1234/CRUD_USING_SPRINGBOOT.git
```

### 2. Open the project

Open the project in **IntelliJ IDEA** or any IDE that supports Spring Boot.

### 3. Configure MySQL

Create a MySQL database:

```sql
CREATE DATABASE crud_db;
```

Then configure your database details in:

```text
src/main/resources/application.properties
```

Example:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/crud_db
spring.datasource.username=root
spring.datasource.password=YOUR_PASSWORD

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

> Replace `YOUR_PASSWORD` with your local MySQL password.

### 4. Run the application

Run the main Spring Boot application class from IntelliJ.

The application will start on:

```text
http://localhost:8080
```

## 🔗 API Endpoints

| Method   | Endpoint    | Description         |
| -------- | ----------- | ------------------- |
| `POST`   | `/api/...`  | Create a new record |
| `GET`    | `/api/...`  | Get all records     |
| `GET`    | `/api/{id}` | Get record by ID    |
| `PUT`    | `/api/{id}` | Update a record     |
| `DELETE` | `/api/{id}` | Delete a record     |

> Update the endpoint names above according to the controller URLs used in the project.

## 🧪 Testing

The REST APIs can be tested using **Postman**.

You can test:

* POST requests for creating data
* GET requests for retrieving data
* PUT requests for updating data
* DELETE requests for deleting data

## 📚 What I Learned

Through this project, I practiced:

* Spring Boot project development
* REST API creation
* CRUD operations
* Spring Data JPA
* MySQL database connectivity
* Repository and controller concepts
* API testing with Postman
* Git and GitHub

## 👨‍💻 Author

**Dibya Mishra**

MCA Student | Aspiring Java Developer

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.
