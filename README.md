# Enterprise Application

This is a Spring Boot enterprise-class N-Layer application developed as part of the CST-339 course.

## Features

- Main Application Module with responsive design
- User Registration Module
- Login Module (simulated authentication)
- Bootstrap-based UI with custom theming
- Thymeleaf templating with layouts

## Technology Stack

- Java 17
- Spring Boot 3.2.3
- Thymeleaf for templating
- Bootstrap 5.3 for responsive design
- Maven for dependency management

## Prerequisites

- Java Development Kit (JDK) 17 or later
- Maven 3.6 or later
- Your favorite IDE (IntelliJ IDEA, Eclipse, VS Code, etc.)

## Getting Started

1. Clone the repository:
   ```bash
   git clone [repository-url]
   ```

2. Navigate to the project directory:
   ```bash
   cd enterpriseapp
   ```

3. Build the project:
   ```bash
   mvn clean install
   ```

4. Run the application:
   ```bash
   mvn spring-boot:run
   ```

5. Access the application:
   Open your web browser and navigate to `http://localhost:8080`

## Project Structure

```
src/main/java/com/clcproject/enterpriseapp/
├── EnterpriseApplication.java
├── controller/
│   ├── AuthController.java
│   └── HomeController.java
└── model/
    ├── User.java
    └── LoginRequest.java

src/main/resources/
├── application.properties
├── static/
│   └── css/
│       └── style.css
└── templates/
    ├── layouts/
    │   └── main.html
    ├── auth/
    │   ├── login.html
    │   └── register.html
    ├── home.html
    └── products.html
```

## Features to be Implemented in Future Milestones

- Database integration
- Spring Security implementation
- Product management functionality
- User profile management
- Additional business logic modules

## Contributing

This is a course project. Contributions are not accepted at this time.

## License

This project is part of academic coursework and is not licensed for public use. 