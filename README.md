#  Drinks Web API 

Utilising Spring Boot and Maven create a Web API to serve back a JSON Response based on a Request using a Test-Driven approach. 

## Use Cases

### Home API Endpoint

As a user, when I do a GET request to the / endpoint, I will see the string message as a response  which says Welcome to the Drinks API! 

### Coffee API Endpoint

* As a user, when I do a GET request to the /coffeelover endpoint, I will see the string message as a  response which says I like coffee!  

* As a user, when I do a GET request to the /coffee endpoint, I will see the JSON response with the id  and the name of the coffee. 


## How to run the web application

1) cd to the project root folder in the command line


2)   ` mvn spring-boot:run `

3) Open   ` HTTP://localhost:8080 ` in your browser.

To run tests use:

* mvn test



## Technology

This project was built using;


* Spring Boot 2.6.7
* Java 17.0.2
* JUnit 5.8.2
* Maven 3.8.5
* IntelliJ 2021.3.2 (Community Edition).
