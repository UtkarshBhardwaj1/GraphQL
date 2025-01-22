# GraphQL Spring Boot Basic Project

This is a basic project that demonstrates how to set up and use **GraphQL** with **Spring Boot** and **Spring Data JPA**. The application provides a simple implementation of a **Book** resource, with CRUD operations exposed via GraphQL mutations and queries.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Project Structure](#project-structure)
- [GraphQL Schema](#graphql-schema)
- [Resolvers](#resolvers)
- [Testing the API](#testing-the-api)
- [Contributing](#contributing)
- [License](#license)

## Technologies Used

- **Spring Boot 3.x**: The project is built using Spring Boot 3.x with Jakarta EE 9.
- **GraphQL Java**: The `spring-boot-starter-graphql` dependency integrates GraphQL with Spring Boot seamlessly.
- **Spring Data JPA**: Used for database interactions, with an H2 in-memory database for simplicity.
- **H2 Database**: Used as an in-memory database for storing Book data.
- **Maven**: The project uses Maven for dependency management and build automation.

## Setup and Installation

### Prerequisites

- **Java 21** or higher
- **Maven 3.8+** (for building the project)
- An IDE (e.g., IntelliJ IDEA, Eclipse) or a text editor to modify the code

### Steps to Run the Project Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/GraphQL-Spring-Boot.git
   cd GraphQL-Spring-Boot

2. **Install dependencies: Run the following Maven command to download all the required dependencies**:


  mvn clean install
  Run the application: Start the Spring Boot application by executing:

  mvn spring-boot:run
  Access the GraphQL endpoint: The default GraphQL endpoint will be available at:

  http://localhost:8080/graphql
