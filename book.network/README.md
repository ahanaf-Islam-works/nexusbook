# BookNexus

Welcome to **BookNexus**, your go-to social network for book lovers! Connect with fellow readers, share your favorite books, write reviews, and discover new reads all in one place.

This project is built using Spring Boot for the backend, Angular for the frontend, Docker for containerization, and Keycloak for identity and access management.

## Getting Started

### Prerequisites

- Java 11 or higher
- Node.js and npm
- Docker
- Keycloak

### Setting Up the Backend

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/booknexus.git
    cd booknexus/backend
    ```

2. Build the project:
    ```bash
    ./mvnw clean install
    ```

3. Run the Spring Boot application:
    ```bash
    ./mvnw spring-boot:run
    ```

### Setting Up the Frontend

1. Navigate to the frontend directory:
    ```bash
    cd ../frontend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Run the Angular application:
    ```bash
    npm start
    ```

### Running with Docker

1. Build and run Docker containers:
    ```bash
    docker-compose up --build
    ```

### Keycloak Setup

1. Download and run Keycloak:
    ```bash
    docker run -p 8080:8080 -e KEYCLOAK_USER=admin -e KEYCLOAK_PASSWORD=admin jboss/keycloak
    ```

2. Access Keycloak at [http://localhost:8080](http://localhost:8080) and create a realm, client, and user.

## Learn More

- [Spring Boot Documentation](https://spring.io/projects/spring-boot) - learn about Spring Boot features and API.
- [Angular Documentation](https://angular.io/docs) - learn about Angular features and API.
- [Docker Documentation](https://docs.docker.com/) - learn about Docker and containerization.
- [Keycloak Documentation](https://www.keycloak.org/documentation.html) - learn about Keycloak features and API.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss your ideas.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
