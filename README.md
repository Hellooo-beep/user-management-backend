# User Management System - Spring Boot Backend

A RESTful API built with Spring Boot and H2 database for managing users. This backend serves the Android mobile application.

## Features

- **Create Users** - Add new users via POST request
- **Read Users** - Fetch all users or specific user
- **Update Users** - Modify existing user information
- **Delete Users** - Remove users from database
- **Full REST API** - Comprehensive CRUD operations
- **In-Memory Database** - H2 for quick testing

## Technology Stack

- **Framework:** Spring Boot 3.x
- **Language:** Java 17
- **Database:** H2
- **Build Tool:** Maven
- **API:** REST

## Getting Started

### Prerequisites

- Java 17 or higher
- Maven 3.6 or higher

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Hellooo-beep/user-management-backend.git
cd user-management-backend
```

2. Build:
```bash
mvn clean install
```

3. Run:
```bash
mvn spring-boot:run
```

Backend runs on: `http://localhost:8080`

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/users | Create user |
| GET | /api/users | Get all users |
| GET | /api/users/{id} | Get user by ID |
| PUT | /api/users/{id} | Update user |
| DELETE | /api/users/{id} | Delete user |

## Testing

Use Postman to test the endpoints above.
