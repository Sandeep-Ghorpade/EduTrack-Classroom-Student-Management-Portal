# 🎓 Student Management System (Spring Boot + MongoDB)

<div align="center">

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.5.0-brightgreen)
![Java](https://img.shields.io/badge/Java-24-orange)
![MongoDB](https://img.shields.io/badge/MongoDB-7.0-green)
![REST API](https://img.shields.io/badge/API-REST-blue)

*A backend REST API application for managing student batch data using Spring Boot and MongoDB*

</div>

---

## 📌 Overview

This project is a **Student Management System** built using Spring Boot.
It provides REST APIs to manage batch details such as creating, retrieving, updating, and deleting records.

The application follows a **layered architecture** and demonstrates backend development concepts like API design, database integration, and service-based logic.

---

## ✨ Features

* 🔧 CRUD operations for batch management
* ⚡ RESTful API design
* 💾 MongoDB integration
* 🏗️ Layered architecture (Controller → Service → Repository)
* 🔍 Health check endpoint
* 📦 Clean and maintainable code structure

---

## 🛠️ Tech Stack

* **Java 24**
* **Spring Boot 3**
* **MongoDB**
* **Spring Data MongoDB**
* **Lombok**
* **Maven**

---

## 📂 Project Structure

```
src/main/java/
│
├── controller/       # API endpoints
├── service/          # Business logic
├── repository/       # Database layer
├── entity/           # Data model
└── Application.java  # Main class
```

---

## ⚙️ Configuration

Update `application.properties`:

```properties
spring.application.name=StudentPortal
spring.data.mongodb.host=localhost
spring.data.mongodb.port=27017
spring.data.mongodb.database=StudentDB
server.port=8080
```

---

## 🚀 Running the Project

### 1. Clone the project

```bash
git clone <your-github-repo-link>
cd student-management-system
```

### 2. Build the project

```bash
mvn clean install
```

### 3. Run the application

```bash
mvn spring-boot:run
```

---

## 🌐 API Endpoints

| Method | Endpoint         | Description              |
| ------ | ---------------- | ------------------------ |
| GET    | /batches         | Get all records          |
| POST   | /batches         | Create new record        |
| GET    | /batches/id/{id} | Get record by ID         |
| PUT    | /batches/id/{id} | Update record            |
| DELETE | /batches/id/{id} | Delete record            |
| GET    | /health          | Check application status |

---

## 🧠 How It Works

* **Controller** handles HTTP requests
* **Service** processes business logic
* **Repository** interacts with MongoDB
* **Entity** represents data structure

---

## 📈 Future Improvements

* 🔐 Authentication (JWT)
* 👥 Role-based access control
* 📊 Dashboard / frontend integration
* 📄 Swagger API documentation

---

## 👨‍💻 Author

**Sandeep Ghorpade**

---

<div align="center">

</div>
