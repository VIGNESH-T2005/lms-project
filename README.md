# Learning Management System (LMS)

## Overview

This project is a **Learning Management System (LMS)** developed using **Java Spring Boot, React, and MySQL**.
The system allows instructors to manage courses and students to view and enroll in available courses. It demonstrates a full-stack web application architecture with a modern frontend and a secure backend.

## Technologies Used

### Backend

* Java
* Spring Boot
* Spring Security
* Hibernate / JPA
* REST API

### Frontend

* React.js
* JavaScript
* HTML
* CSS

### Database

* MySQL

### Build Tools

* Maven
* npm

## Features

### Authentication

* Secure user login
* Role-based access control

### Instructor Module

* Create courses
* Manage course details
* Assign courses to semesters

### Student Module

* View available courses
* Access semester courses

### System

* RESTful API communication
* Database integration using JPA
* Secure password encryption

## System Architecture

```
React Frontend
      |
      | REST API
      |
Spring Boot Backend
      |
      | JPA / Hibernate
      |
MySQL Database
```

## Installation

### Backend Setup

1. Open the project in an IDE.
2. Configure MySQL in `application.properties`.
3. Run the Spring Boot application.

Backend server runs at:

```
http://localhost:8085
```

### Frontend Setup

Navigate to the frontend folder and run:

```
npm install
npm start
```

Frontend runs at:

```
http://localhost:3000
```

## Future Improvements

* Course enrollment system
* Student dashboard
* Instructor analytics
* File upload for course materials

## Author

Vignesh
