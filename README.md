# microservice-config
This is a project containing configurations of microservice tutorial project

# Spring Boot Microservices Tutorial

This GitHub repository contains the source code and instructions for a microservices tutorial using Spring Boot 3. In this tutorial, we will create three microservices: `orderservice`, `paymentservice`, and `productservice`. These microservices will work together to simulate a basic e-commerce system where users can place orders, make payments, and view product information.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Microservices Overview](#microservices-overview)
- [Project Structure](#project-structure)
- [Running the Microservices](#running-the-microservices)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before you start, make sure you have the following prerequisites installed on your development machine:

- [Java JDK 11](https://www.oracle.com/java/technologies/javase-downloads.html)
- [Apache Maven](https://maven.apache.org/download.cgi)
- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Getting Started

To get started with this tutorial, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/spring-boot-microservices-tutorial.git
   ```

2. Navigate to the project directory:

   ```bash
   cd spring-boot-microservices-tutorial
   ```

3. Follow the instructions in the README files of each microservice to set up and run them.

## Microservices Overview

### `orderservice`

The `orderservice` microservice is responsible for handling customer orders. It provides endpoints for creating new orders, retrieving order details, and managing order status.

### `paymentservice`

The `paymentservice` microservice handles payment processing. It allows users to make payments for their orders and provides payment status information.

### `productservice`

The `productservice` microservice manages product information. It provides endpoints for querying product details, listing available products, and updating product data.

## Project Structure

The project structure is organized as follows:

- `orderservice/`: Source code and resources for the `orderservice` microservice.
- `paymentservice/`: Source code and resources for the `paymentservice` microservice.
- `productservice/`: Source code and resources for the `productservice` microservice.

Each microservice follows a standard Spring Boot project structure.

## Running the Microservices

To run the microservices locally, you will need to build and start each microservice separately. Refer to the README files in each microservice's directory for detailed instructions on how to build and run them.

## API Documentation

- API documentation for each microservice can be found in their respective README files.
- Swagger UI is included for easy API exploration. You can access the Swagger UI for each microservice by visiting the following URLs:
  - `orderservice` Swagger UI: `http://localhost:8081/swagger-ui.html`
  - `paymentservice` Swagger UI: `http://localhost:8082/swagger-ui.html`
  - `productservice` Swagger UI: `http://localhost:8083/swagger-ui.html`

## Contributing

Contributions to this tutorial project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
