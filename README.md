# Task 1 - Spring Boot & Thymeleaf Application

This is a simple Spring Boot web application created as part of the university assignment. It demonstrates basic routing using Spring MVC Controllers and dynamic HTML rendering with Thymeleaf.

## Features
- **Home Endpoint (`/`)**: Returns a plain text welcome message directly using `@ResponseBody`.
- **Greeting Endpoint (`/greeting`)**: Renders a dynamic HTML page using Thymeleaf templates, accepting an optional `name` parameter.

## Technology Stack
- Java 17 / 21
- Spring Boot
- Spring Web
- Thymeleaf
- Maven

## How to Run
1. Open the project in IntelliJ IDEA.
2. Let Maven resolve all dependencies.
3. Run the `Task1Application.java` file.
4. Open your browser and navigate to:
   - http://localhost:8080/
   - http://localhost:8080/greeting?name=John
