# Combat Hub Backend

## Project Overview
Combat Hub is a REST API designed to support the Combat Hub platform. It provides functionalities for user authentication, email verification, and more.

## Getting Started

### Prerequisites
- **Java 17**
- **Maven**
- **MySQL**

### Installation
1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd combat_hub

## Set up the development environment:
``` bash
  ./mvnw clean install


## Configure the database:

1. Create a MySQL database.
2. Update the application.properties file with your database credentials.

## Run the application locally:


## Technologies Used

- Spring Boot
- Spring Security
- Spring Data JPA
- Flyway
- MySQL
- Lombok
- Java JWT
- SendGrid

## API Documentation

### Endpoints

- `/login` - User login
- `/register` - User registration
- `/verification-code/new-code` - Generate new verification code
- `/verification-code` - Verify code

For detailed API documentation, refer to the API Documentation.

## Contributing Guidelines

1. Fork the repository.
2. Create a new branch:

```git checkout -b feature-branch

3. Make your changes.
4. Commit your changes:
5. Push to the branch:

``` git push origin feature-branch

6. Open a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
