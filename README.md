
# Superheroes Spring Boot Application

This is a demo project for a Spring Boot application that integrates with various technologies such as Redis, PostgreSQL, H2 Database, JWT Security, and OpenAPI 3. The project also includes a frontend built with Angular, packaged together with the backend in a single JAR file.

---

## Project Structure
```
.
├── .github/
│   └── workflows/
├── .idea/
├── .vscode/
├── frontend/
│   ├── .angular/
│   ├── src/
│   ├── angular.json
│   ├── karma.conf.js
│   ├── package.json
│   ├── README.md
│   ├── tsconfig.app.json
│   ├── tsconfig.json
│   └── tsconfig.spec.json
├── logs/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/example/springbootsuperheroes/superheroes/
│   │   └── resources/
│   ├── test/
│   │   ├── java/
│   │   │   └── com/example/springbootsuperheroes/superheroes/
│   │   └── resources/
├── mvnw
├── mvnw.cmd
├── pom.xml
└── system.properties
```

---

## Dependencies
The project uses the following dependencies:

- **Spring Boot Starter Data JPA**
- **PostgreSQL**
- **Spring Boot Starter Data Redis**
- **Spring Data Redis**
- **Jedis**
- **H2 Database**
- **Spring Boot Starter Web**
- **Spring Boot Starter Log4j2**
- **Spring Boot Starter Validation**
- **Spring Boot DevTools**
- **Lombok**
- **Spring Boot Starter Test**
- **ModelMapper**
- **SpringDoc OpenAPI UI**
- **SpringDoc OpenAPI Data Rest**
- **Spring Boot Starter Security**
- **JJWT (Java JWT)**
- **JUnit**

---

## Build and Run

### Prerequisites
- **Java 17**
- **Maven**
- **Node.js and npm**

### Building the Project
To build the project, run the following command:
```bash
mvn clean install
```

### Running the Application
To run the application, use the following command:
```bash
java -jar target/superheroes.jar
```

### Running Tests
To run the tests, use the following command:
```bash
mvn test
```

---

## Configuration

### Application Properties
The application properties are configured in:
- `src/main/resources/application.properties`
- `src/main/resources/application.yml`

### Security Configuration
The security configuration is defined in `SecurityConfig`.

### Redis Configuration
The Redis configuration is defined in `RedisConfig`.

### Logging
The logging configuration is defined in `log4j2-spring.xml`.

---

## Packaging
The project uses the `frontend-maven-plugin` to package the Spring Boot backend and Angular frontend into a single JAR file.

---

## License
This project is licensed under the [MIT License](LICENSE).
