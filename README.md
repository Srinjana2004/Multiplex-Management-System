# 🎬 Multiplex Management System

An end-to-end web application for automating multiplex theater operations, including **movie scheduling, seat reservation, ticket booking, payment processing, cancellation, and administrative reporting**.

## 📚 Academic Details

* **Paper Code:** PCC-IT 651
* **Subject:** Software Engineering Lab
* **Institution:** University Institute of Technology, The University of Burdwan
* **Department:** Information Technology
* **Guide:** Mr. Dibyadeep Nandi Sir
* **Group:** 3
* **Submission Date:** 07/08/2026

## 👥 Team Members

* Rahul Majumder — 2023-3012
* Priyotosh Mandal — 2023-3013
* Subhra Khan — 2023-3014
* Srinjana Sahana — 2023-3015
* Piyush Yadav — 2023-3016

## ✨ Features

### 👤 User Module

* User Registration & Login
* Browse Movies and Shows
* Interactive Seat Selection
* Real-time Seat Availability
* Online Ticket Booking
* Multiple Payment Methods
* Booking History & E-Tickets
* Ticket Cancellation & Refund

### 🛡️ Admin Module

* Admin Dashboard
* Movie Management
* Screen & Seat Management
* Show Scheduling
* Ticket Price Management
* Booking Management
* Sales & Revenue Reports

## ⚙️ Tech Stack

**Backend:** Java, Spring Boot, Spring Data JPA, Hibernate
**Frontend:** HTML5, CSS3, JavaScript / React.js
**Database:** MySQL
**Server:** Embedded Apache Tomcat
**API:** RESTful APIs, JSON
**Build Tool:** Maven / Gradle

## 📐 Design Diagrams

* Context Diagram (DFD Level 0)
* DFD Level 1 & Level 2
* ER Diagram
* Use Case Diagram
* Class Diagram

## 💻 Requirements

* JDK 17+
* MySQL 8.0+
* Maven / Gradle
* IntelliJ IDEA / Eclipse
* Modern Web Browser

## 🚀 Setup

### 1. Create Database

```sql
CREATE DATABASE multiplex_db;
```

### 2. Configure MySQL

Update `src/main/resources/application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/multiplex_db?useSSL=false&serverTimezone=UTC
spring.datasource.username=YOUR_MYSQL_USERNAME
spring.datasource.password=YOUR_MYSQL_PASSWORD
spring.jpa.hibernate.ddl-auto=update
```

### 3. Run Application

```bash
mvn spring-boot:run
```

Application runs at:

```text
http://localhost:8080
```

## 📁 Project Structure

```text
MMS-Ferry/
├── src/
│   └── main/
│       ├── java/com/multiplex/
│       │   ├── controller/
│       │   ├── model/
│       │   └── repository/
│       └── resources/
│           ├── static/
│           └── application.properties
├── multiplex_db.sql
├── pom.xml
└── README.md
```

## 🙏 Acknowledgement

We sincerely thank **Mr. Dibyadeep Nandi Sir** for his valuable guidance, feedback, and continuous support throughout this project.

Developed as an academic project for the **Software Engineering Lab, Department of Information Technology, University Institute of Technology, The University of Burdwan**.
