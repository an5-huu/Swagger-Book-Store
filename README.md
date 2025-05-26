# Swagger Book Store Microservices

A microservices-based implementation of the Swagger Book Store API using Java Spring Boot.

## Project Structure

The project is organized into multiple microservices:

- **Book Service**: Manages book-related operations
- **Order Service**: Handles order processing and management
- **User Service**: Manages user authentication and profiles
- **API Gateway**: Routes requests to appropriate microservices

## Prerequisites

- Java 17 or higher
- Maven
- PostgreSQL (for database)

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/an5-huu/Swagger-Book-Store
cd swagger-bookstore
```

### 2. Build the Project

```bash
mvn clean install
```

### 3. Run the Services

Each service can be run independently:

```bash
# Run Book Service
cd book-service
mvn spring-boot:run

# Run Order Service
cd order-service
mvn spring-boot:run

# Run User Service
cd user-service
mvn spring-boot:run

# Run API Gateway
cd api-gateway
mvn spring-boot:run
```


## Configuration

Each service has its own `application.properties` file with the following configurations:

- Server port
- Database connection details
- Service discovery settings
- API Gateway routing rules

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 
