# Employee Management System

## 📌 Project Overview

The Employee Management System is a full-stack web application developed to manage employee information efficiently. It allows users to perform CRUD (Create, Read, Update, and Delete) operations on employee records.

The application uses React for the frontend, Spring Boot for the backend, and MySQL for database management. Spring Data JPA is used to interact with the database.

## 🚀 Features

- Add new employee details
- View all employee records
- Update existing employee information
- Delete employee records
- Store and manage employee data in MySQL
- RESTful API integration between frontend and backend
- Responsive and user-friendly interface

## 🛠️ Technologies Used

### Frontend
- React.js
- HTML5
- CSS3
- JavaScript

### Backend
- Java
- Spring Boot
- Spring Data JPA
- REST APIs
- Maven

### Database
- MySQL

### Tools
- Visual Studio Code
- IntelliJ IDEA / Eclipse
- Postman
- MySQL Workbench
- Git and GitHub

## 🏗️ Project Architecture

React Frontend → Spring Boot REST API → Spring Data JPA → MySQL Database

## 📂 Project Structure

```text
Employee-Management-System/
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
│
├── backend/
│   ├── src/main/java/
│   │   └── in/nandini/
│   │       ├── controller/
│   │       ├── service/
│   │       ├── repository/
│   │       └── entity/
│   ├── src/main/resources/
│   │   └── application.properties
│   └── pom.xml
│
└── README.md
```

*Note: Update the folder names and package structure to match your actual project.*

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone <your-github-repository-url>
cd Employee-Management-System
```

### 2. Configure the MySQL Database

Create a database in MySQL:

```sql
CREATE DATABASE employee_db;
```

Update your backend `application.properties` file:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/employee_db
spring.datasource.username=your_username
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

Replace the username and password with your local MySQL credentials.

### 3. Run the Backend

Open the backend folder and run:

```bash
mvn spring-boot:run
```

The Spring Boot application will start on the configured port, usually `8080`.

### 4. Run the Frontend

Open another terminal and navigate to the frontend folder:

```bash
npm install
npm start
```

If your React project was created using Vite, use:

```bash
npm install
npm run dev
```

Open the local URL displayed in the terminal.

## 🔗 API Endpoints

Example REST API endpoints (adjust them to match your backend implementation):

| Method | Endpoint | Description |
|---|---|---|
| GET | `/api/employees` | Retrieve all employees |
| GET | `/api/employees/{id}` | Retrieve an employee by ID |
| POST | `/api/employees` | Add a new employee |
| PUT | `/api/employees/{id}` | Update employee details |
| DELETE | `/api/employees/{id}` | Delete an employee |

## 🎯 Learning Outcomes

- Learned how to build REST APIs using Spring Boot.
- Practiced CRUD operations using Spring Data JPA.
- Connected a Java backend to a MySQL database.
- Developed frontend components using React.
- Integrated frontend and backend applications.
- Improved understanding of full-stack application development.

## 🔮 Future Enhancements

- User authentication and authorization
- Employee search and filtering
- Pagination and sorting
- Form validation and error handling
- Employee profile image upload
- Deployment to a cloud platform

## 👩‍💻 Author

**Bandi Nandini**

B.Tech in Computer Science and Engineering

## 📄 License

This project is created for educational and learning purposes.
