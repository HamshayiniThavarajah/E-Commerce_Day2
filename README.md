# E-Commerce_Day2
# Spring Boot Application 

## Overview 
This is a simple Spring Boot application that provides RESTful API endpoints to return basic text messages. The application is structured with a controller that maps specific routes to return responses.

## Requirements 
- Java 17 or later
- Maven
- Spring Boot

## Installation 
1. Clone the repository:
   ```sh
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```sh
   cd <project-directory>
   ```
3. Build the application using Maven:
   ```sh
   mvn clean install
   ```

## Running the Application ▶
Run the application using the following command:
```sh
mvn spring-boot:run
```

## API Endpoints 

### GET `/app/msg`
Returns a simple message:
```json
"Hello SpringBoot"
```

### GET `/app/name`
Returns another message:
```json
"My Name is SpringBoot"
```

## Technologies Used 
- Spring Boot
- Java
- Maven

## Purpose 
This application is designed to introduce the fundamentals of Spring Boot and RESTful API development, serving as a foundation for further learning and advanced topics like dependency injection, service layers, and database integration.

