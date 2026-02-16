# Employee / Admin Todos REST API

This repository contains a Spring Boot REST API project developed alongside the Udemy course: “Develop Real-Time Spring Boot 4 RESTful Endpoints: CRUD, JWTs, OpenAPI, Swagger, Auth, H2 Embedded DB, MySQL” with the goal to serve as a portfolio project demonstrating my skills with Java, Spring Boot and REST APIs.

<br>

## 📌 Project Overview

This application is a Todos management system with role-based access control. It exposes multiple RESTful endpoints that allow users and administrators to manage todos and users securely.

The API supports:
- User registration and authentication using JWTs
- CRUD operations for todos
- Role-based authorization for user vs admin actions

<br>

## 📂 Project Structure

The repository is organized following standard Spring Boot best practices, separating concerns such as:
- Controllers
- Services
- Repositories
- Security configuration
- Models / Entities

Each commit corresponds closely to course lessons to clearly show feature progression.

<br>

## 👥 User Roles & Features
### 👤 Regular Users

- Register and log in
- Authenticate using JWT-based security
- Fetch their own user information
- Create, read, update, and delete their own Todos only

### 🛠 Admin Users

- Retrieve a list of all users
- Promote regular users to admin
- Delete non-admin users

<br>

## 🔐 Authentication & Security

- JWT-based authentication
- Secure login and registration endpoints
- Role-based access control (USER / ADMIN)
- Protected endpoints using Spring Security

<br>

## 🧱 Tech Stack

- Java
- Spring Boot
- Spring Web
- Spring Data JPA
- Spring Boot DevTools
- Spring Security
- JWT (JSON Web Tokens)
- MySQL
- OpenAPI / Swagger
- Maven

<br>

## ▶️ How to Run Locally

Follow the steps below to run the application on your machine.

### 1️⃣ Start MySQL using Docker

Make sure Docker is running, then execute:

`docker run -d -e MYSQL_ROOT_PASSWORD=secret -e MYSQL_DATABASE=tododb --name mysqldb -p 3307:3306 mysql:8.0`

This will:
- Create a MySQL container
- Set the root password to secret
- Create a database named tododb
- Expose MySQL on port 3307 locally

### 2️⃣ Run the Spring Boot Application

Open the project in your favorite IDE (IntelliJ, VS Code, Eclipse, etc.) and start the application.

The API will run by default on:

`http://localhost:8080`

### 3️⃣ Access Swagger / OpenAPI Documentation

Once the application is running, open your browser and go to:

`http://localhost:8080/docs`

From there you can explore and test all available endpoints.

<br>

## 🚀 Purpose of This Repository

This project is:
- A hands-on learning exercise
- A demonstration of real-world REST API development
- A showcase of backend development skills with Spring Boot
- It emphasizes clean architecture, incremental development, and industry-standard practices.

Feel free to explore the commit history to follow the development step-by-step.
