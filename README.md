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

## 🚀 Purpose of This Repository

This project is:
- A hands-on learning exercise
- A demonstration of real-world REST API development
- A showcase of backend development skills with Spring Boot
- It emphasizes clean architecture, incremental development, and industry-standard practices.

Feel free to explore the commit history to follow the development step-by-step.
