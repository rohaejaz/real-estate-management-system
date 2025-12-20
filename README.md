# Real Estate Management System

A full-stack web application for managing real estate property listings, users, and inquiries.  
This project demonstrates end-to-end development using .NET on the backend and Angular on the frontend, following clean and scalable architecture principles.

---

## Overview
The Real Estate Management System enables administrators and users to efficiently manage property data, handle user interactions, and process inquiries.  
It is designed with a strong focus on clean architecture, scalability, and maintainability, making it suitable for real-world enterprise applications.

---

## Key Features
- Secure user authentication and authorization
- Role-based access control (Admin / User)
- Property listing management (Create, Read, Update, Delete)
- Advanced search and filtering of properties
- User inquiry and contact management
- RESTful API communication between frontend and backend
- Modular and scalable codebase following SOLID principles

---

## Tech Stack

### Backend
- C#
- ASP.NET Core (.NET)
- RESTful APIs
- Entity Framework Core

### Frontend
- Angular
- TypeScript
- HTML, CSS

### Database
- SQL Server

### Tools & Practices
- Git & GitHub
- Clean Architecture
- SOLID principles
- Layered application design

---

## Architecture
The application follows a layered architecture:

- **Presentation Layer:** Angular frontend UI  
- **Application Layer:** Business logic and use cases  
- **Data Access Layer:** Entity Framework Core with SQL Server  

This separation ensures maintainability, testability, and ease of future enhancements.

---

## Setup Instructions

### Prerequisites
- .NET SDK
- Node.js & npm
- SQL Server

### Steps
1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/real-estate-management-system.git
Configure the database connection string in appsettings.json

Run the backend API

dotnet run


Navigate to the frontend folder, install dependencies, and start the Angular application

npm install
ng serve


Access the application in your browser at

http://localhost:4200

