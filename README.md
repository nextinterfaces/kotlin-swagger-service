
# Spring Boot Swagger Kotlin Project

This project is a Kotlin-based RESTful API using Spring Boot, integrated with Swagger for API documentation.

## Features
- Kotlin and Spring Boot backend
- Swagger integration for interactive API documentation
- Example REST endpoints

## Prerequisites
- Java 11 or newer
- Gradle or use the included Gradle wrapper

## Getting Started

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd kotlin-swagger-service
   ```

2. **Build and run the project**
   ```bash
   ./gradlew clean bootRun
   ```

3. **Access the Swagger UI**
   Open a browser and navigate to [http://localhost:8080/swagger-ui.html](http://localhost:8080/swagger-ui.html) to view and test the API endpoints.

## Project Structure
- **`src/main/kotlin/com/hendisantika/swagger/kotlin/controller/`** - Contains the API controllers
- **`src/main/resources/application.properties`** - Spring Boot application configuration
- **`build.gradle.kts`** - Project dependencies and build configuration

## API Documentation
Swagger UI provides interactive documentation for all API endpoints, making it easy to test and understand each API's inputs and outputs.

## Additional Commands
- **Run tests**:
  ```bash
  ./gradlew test
  ```
  
- **Build the project**:
  ```bash
  ./gradlew build
  ```

## License
This project is open-source and available under the [MIT License](LICENSE).
