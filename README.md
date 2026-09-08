# Backend Order Management System

A robust, RESTful backend service for managing customers, products, and orders, built using Java and Spring Boot.

## Architecture
- **Layered Design:** Separates concerns into Controllers, Services, and Repositories following Object-Oriented Programming best practices.
- **Data Persistence:** Utilizes MySQL for persistent storage and optimized database queries.
- **Containerization:** The application and database are fully containerized using Docker and Docker Compose.
- **CI/CD:** Automated deployment to AWS EC2 using GitHub Actions.

## Features
- Full CRUD operations for orders.
- REST API endpoints for order creation, status updates, and retrieval.
- Automated database schema updates via Hibernate (`ddl-auto=update`).
- Exception handling and structured JSON responses.

## Tech Stack
- **Language:** Java 17
- **Framework:** Spring Boot, Spring Data JPA
- **Database:** MySQL 8.0
- **Deployment:** Docker, AWS EC2

## Run Locally
1. Clone the repository.
2. Run using Docker Compose:
   ```bash
   docker-compose up -d --build
   ```
3. The API will be available at `http://localhost:8080/api/orders`.


## Community
Contributions are always welcome. See CONTRIBUTING.md for details.
