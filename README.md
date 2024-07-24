# Cloud Parking

This project aims to develop a comprehensive parking management system. The application was built with Spring Boot and features a set of RESTful APIs to control parking operations. Swagger was integrated to provide comprehensive documentation and testing capabilities for the APIs. Additionally, thorough unit testing was conducted to ensure the reliability and correctness of the system's core components.

## Main Features:

* **Entry and Exit Control:** Accurate recording of vehicle entries and exits, including information such as license plate, model, date, and time.
* **Tariff Calculation:** Automatic calculation of the amount to be charged based on the length of stay and configurable pricing rules.
* **Robust Security:** Implementation of authentication and authorization using Spring Security to ensure that only authorized users can access API resources.
* **Data Persistence:** Use of the PostgreSQL database to store information securely and reliably.
* **Quality Assurance:** Comprehensive coverage of unit and integration tests to ensure system functionality and stability.
* **Cloud Availability:** Deployment of the application on the Heroku platform, making it globally accessible over the internet.
* **API Documentation and Testing:** Integration of Swagger to provide interactive API documentation and testing capabilities.
* **Unit Testing:** Thorough unit testing of core components to ensure reliability and correctness.

## Technologies Used:

* **Spring Boot:** Main framework for application development.
* **Spring Security:** Library for API security.
* **PostgreSQL:** Relational database for data persistence.
* **Heroku:** Cloud platform for hosting and deploying the application.
* **Swagger:** Tool for API documentation and testing.

## Contributions:

Contributions to the project are welcome! Feel free to open issues, submit pull requests, or suggest improvements.

## Starting PostgresDB

### Run database
docker run --name parking-db -p 5432:5432 -e POSTGRES_DB=parking -e POSTGRES_USER=admin -e POSTGRES_PASSWORD=123 -d postgres:10-alpine

### Stop database
docker stop parking-db

### Start database
docker start parking-db
