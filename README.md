# api-gateway

This project is an API Gateway built with Spring Boot.

## Features
- Centralized routing for microservices
- Request filtering and validation
- Configuration via `application.yml` and `application.properties`

## Getting Started

### Prerequisites
- Java 17 or newer
- Maven

### Build and Run
```bash
mvnw spring-boot:run
```

### Configuration
Edit `src/main/resources/application.yml` or `application.properties` to customize routes and gateway settings.

## Project Structure
- `src/main/java/com/example/api_gateway/` - Main source code
- `src/main/resources/` - Configuration files
- `pom.xml` - Maven build file

## Testing
Run tests with:
```bash
mvnw test
```

## License
MIT
