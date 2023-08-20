# Project Title

Book my consulting API serves backend services to manage doctors appointment. It has been built on Spring platform using spring-boot framework.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need following softwares before running this applic
ation.

1. Java 8 SDK
2. Apache Maven 3.3 build tool
3. JAVA_HOME environment variable must be set before using Apache Maven with Java 8 SDK
4. MySQl version 8.14
5. Your favorite IDE such as Intellij/Eclipse (optional)
6. Postman Client for REST APIs testing (optional)

### Installing and Deployment

A step by step guide that helps you get a development environment running

1. Create database named `consultation` with associated owner `root` and execute the SQL commands in the file `/src/main/resources/DBLoadScript.sql`

2. update the user name password in the `/src/main/appliaction.properties` file
     ```
        spring.datasource.username={username}
        spring.datasource.password={password}

3. Build the project using maven command `mvn clean install -DskipTests`. First time build will consume time as it downloads all dependencies.

4. start the application using command `mvn spring-boot:run`