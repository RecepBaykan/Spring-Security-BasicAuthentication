# Spring Security Basic Authentication

## Project Overview

This project demonstrates how to implement Basic Authentication using Spring Security in a Spring Boot application. It includes a custom `AuthenticationProvider` and `UserDetailsService` to handle user authentication and authorization.

## Features

- Basic Authentication for secure user login
- Custom `AuthenticationProvider` for user authentication
- Custom `UserDetailsService` to load user details and verify passwords
- BCrypt algorithm used for secure password storage and verification
- Crud operations

## Prerequisites

- Java 11 or higher
- Spring Boot 3.x
- Spring Security
- Lombok
- Maven
- A database (e.g., H2, MySQL, PostgreSQL)

## Installation and Run

   ```bash
   git clone https://github.com/RecepBaykab/Spring-Security-BasicAuthentication.git
   cd Spring-Security-BasicAuthentication-main
   mvn spring-boot:run
  ```

### Root Account
username = root
password = 1234


### config/AccountWebSecurity.java
You can edit your http request configuration at this class.


    

   
