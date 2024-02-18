# aws-demo-api

aws demo api, using aws cloud services

![Project Logo](logo.png) 

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Docker Deployment](#docker-deployment)
    - [Prerequisites](#prerequisites-1)
    - [Build the Docker Images](#build-the-docker-images)
    - [Deploy with Docker Compose](#deploy-with-docker-compose)
- [Accessing the Web Service](#accessing-the-web-service)
- [Cleaning Up](#cleaning-up)
- [Documentation and Code Quality](#documentation-and-code-quality)

## Features

- **Technology Stack:**
  - Language: C#
  - Framework: .NET Core 8
  - Frontend: React
  - Database: DynamoDB
    - Fast and Flexible NoSQL Database for Low Latency Data at Any Scale. 
  - Containerization: Docker and Docker Compose
  - Message Queue: AWS SQS
    - lets you send, store, and receive messages between software components at any volume, without losing messages or requiring other services to be available.
  - Cache: ElastiCache
    - Fully Managed Redis & Memcached Open-Source Database w/ Scalability
  - Tests:
    - Functional Tests
      - Integration tests
      - Unit tests(xunit, Moq)

- **Local Development:**
  The service is designed to run locally without any external dependencies, making it easy to set up and test.

- **Cache Layer:**
  A cache layer is thoughtfully implemented to optimize performance by reducing data retrieval operations.

- **Architectural Design:**
  Our project boasts a meticulously designed architecture that includes the selection of components and services to ensure scalability and maintainability.

- **Code Organization and Structure:**
  The codebase adheres to industry best practices for code organization and structure, ensuring a smooth development experience.

- **Documentation and Code Quality:**
  We take pride in our extensive documentation, explaining the project's architecture, components, and development practices. The codebase follows impeccable coding standards, ensuring maintainability and reliability.

- **Commit History and Version Control:**
  We maintain a pristine and well-organized commit history, following best version control practices, including atomic commits and meaningful commit messages.

- **Best Coding Practices:**
  Our codebase adheres to industry-standard coding practices, including naming conventions, error handling, testing, and security measures.

## Getting Started

Let's get you started !

### Prerequisites

Before you dive in, ensure you have the following installed:

- [.NET Core 7 SDK](https://dotnet.microsoft.com/download/dotnet/7.0)
- [Angular CLI](https://angular.io/guide/setup-local)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/J0s3Barbosa/aws-demo-api.git
   ```
2. Set up the backend:
  ```bash
cd Backend
dotnet restore
dotnet build
dotnet run
   ```

3. Set up the frontend:

  ```bash
cd Frontend
npm install
ng serve
   ```



