# ClassManager — Spring Boot collaboration practice

A Spring Boot group-practice project that models students and teachers with JPA entities persisted to PostgreSQL.

## Tech stack

- Java 21
- Spring Boot 3.5.3 (spring-boot-starter-web, spring-boot-starter-data-jpa)
- PostgreSQL
- Maven wrapper

## What it does

- Defines JPA entities for students (name, age) and teachers
- Provides Spring Data JPA repositories and service classes for students and teachers
- Uses a layered package layout (model, repository, service, controller)

## How to run

1. Set the database environment variables used in `application.properties`:
   ```bash
   export DB_URL=jdbc:postgresql://localhost:5432/classmanager
   export DB_USER=your-user
   export DB_PASSWORD=your-password
   ```
2. Start the app: `./mvnw spring-boot:run`
