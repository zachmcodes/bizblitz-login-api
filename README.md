# bizblitz-login-api
Login API

Overview

The login-api is a Spring Boot service that handles user authentication and authorization. It manages user registration, login, and role assignments.

Features

    •    User registration and management.
    •    Password hashing and secure authentication.
    •    Role-based access control.

Installation

    1.    Prerequisites:
    •    Java 11+
    •    Maven or Gradle
    2.    Setup:
    •    Clone the repository:
    git clone https://github.com/yourusername/login-api.git
    •    Navigate to the project directory and build the project:
    cd login-api
    ./mvnw clean install
    •    Configure the application.properties or application.yml with your database settings.

    3.    Run the Application:
    •    Start the application:
    ./mvnw spring-boot:run
    •    The service will be available at http://localhost:8000.

Endpoints

    •    POST /api/auth/register: Register a new user.
    •    POST /api/auth/login: Authenticate an existing user.

Testing

    •    Unit and integration tests are included.
    •    To run tests:
    ./mvnw test
