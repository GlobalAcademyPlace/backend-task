# .NET Interview Task: Microservices System with Repository Pattern

## Introduction

This interview task is designed to evaluate your proficiency in building a microservices-based system using .NET Core, focusing on the Repository pattern with Entity Framework Core (EF Core) for data access. The project aims to assess your understanding of microservices architecture, design patterns, and your ability to implement a scalable, maintainable system.

## Objective

Develop a microservices-based system that demonstrates the use of the Repository pattern for data access with EF Core. The system should consist of at least two microservices that interact with each other and perform CRUD operations on a shared database.

## Requirements

### Technology Stack

- .NET 6 for building the microservices.
- Entity Framework Core for ORM.
- A SQL database (e.g., SQL Server, PostgreSQL) for data storage.
- Docker for containerizing the microservices.
- Any additional libraries or frameworks you find necessary for completing the task.

### Functionality

Your microservices system should support the following functionalities:

- **Microservice 1**: Manages users (e.g., registration, login, forgot password, activation account).
- **Microservice 2**: Manages tasks or another domain entity relevant to your system (e.g., create, update, delete, list tasks).
- Implement communication between microservices using asynchronous messaging.
- Ensure each microservice uses the Repository pattern for data access to abstract the data layer.

### Code Quality

- Follow clean code principles and best practices in .NET development.
- Apply the Repository pattern correctly to abstract the data layer in each microservice.
- Adhere to SOLID principles and design patterns where applicable.

### Testing

- Write unit and integration tests for both microservices.
- Demonstrate the use of mock objects or testing databases for testing the data access layer.

### Containerization

- Dockerize your microservices for easy setup and deployment.
- Include a `docker-compose.yml` file for orchestrating the microservices and the database.

## Submission Guidelines

- Push your code to a private GitHub repository.
- Make sure your repository includes a `.gitignore` file suitable for .NET and Docker projects.
- Document setup and run instructions in a `README.md` file at the root of your repository.
- Share the repository with venimirp@gmail.com

## Evaluation Criteria

- **Architecture**: Does the system follow microservices architecture principles?
- **Functionality**: Does the system meet the specified functional requirements?
- **Code Quality**: Is the code clean, well-organized, and following best practices?
- **Repository Pattern Implementation**: Is the Repository pattern correctly implemented and used for data access?
- **Testing**: Are there comprehensive tests, and do they adequately cover the functionality?
- **Containerization**: Are the microservices and database correctly dockerized?

## Additional Notes

- You are encouraged to document any design decisions and assumptions made during development in your `README.md`.
- If you face any challenges, please describe them in your documentation.
