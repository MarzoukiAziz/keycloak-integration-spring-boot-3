# Keycloak Integration with Spring Boot 3

This project demonstrates how to secure a Spring Boot 3 application using Keycloak, an open-source Identity and Access Management tool.

## Features

- **Single Sign-On (SSO)** with OpenID Connect
- **Role-Based Access Control (RBAC)**
- **Fine-Grained Authorization**

## Prerequisites

- Java 17+
- Maven
- Keycloak Server 21+

## Getting Started

Follow these steps to set up the project on your local machine for development and testing.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/MarzoukiAziz/keycloak-integration-spring-boot-3
   ```
2. Navigate into the project directory:
   ```bash
   cd keycloak-integration-with-spring-boot-3
   ```
3. Build the project using Maven:
   ```bash
   mvn clean install
   ```
4. Run the Spring Boot application:
   ```bash
   mvn spring-boot:run
   ```

### Keycloak Setup

1. Start Keycloak using Docker Compose:
   ```bash
   docker-compose up -d
   ```
2. Open the [Keycloak Admin Console](http://localhost:9090) in your browser.
3. Create a new **Realm** and name it `moazmar`, or update the `application.yml` file to specify your custom realm name.
4. Create **Roles**.
5. Create **Users**.
6. Assign roles to users.

## Usage

🚧 **Work in Progress** (TBD)

## Contributing

Contributions are welcome! If you plan to make significant changes, please open an issue first to discuss them.  
Make sure to update tests where applicable.

## License

This project is licensed under the MIT License. See the `LICENSE.md` file for details.

---

### Key Improvements:

- Fixed grammar and typos (e.g., "Real" → "Realm," "ut" → "it").
- Improved clarity and readability.
- Used bold formatting for key points.
- Standardized project directory name for consistency.

Let me know if you want further refinements! 🚀
