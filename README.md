# Petstore Service Automation
This project includes sample test cases on the https://petstore.swagger.io/
- Find By Pet Status
- Find Pet By Id
- Get Orders

## Features

- Listing requested pets
- View pet status
- Order placed for purchasing the pet

## Requirements

- [Java SDK](https://www.oracle.com/java/technologies/downloads/)
- [Maven](https://maven.apache.org/)
- [Alllure Report](https://docs.qameta.io/allure-report/)

## Installation

Install the dependencies and then run test class


```sh
git clone https://github.com/aysenurck/pet-service.git
mvn -test
allure serve allure-results
```

