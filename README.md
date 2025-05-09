<!-- ============================================  TITLE ======================================================  -->
# REST API for TourNest Trip Management System
<!-- ============================================  DETAILS ======================================================  -->

<li>An Trip Managment Platform like MakeMyTrip or Yatra.
<li>An developement of RESTful API for an application. This API performs all the fundamental CRUD operations of any with user validation at every step.
<br>

<!-- ============================================  FEATURES ======================================================  -->

  
## Features

* Customer and Admin authentication & validation with session uuid having.
* Admin Features:
    * Administrator Role of the entire application
    * Only registered admins with valid session token can add/update/delete customer from main database
    * Admin can access the details of different customers and trip bookings
* Customer Features:
    * Registering themselves with application, and logging in to get the valid session token
    * Viewing list of available buses, packages, hotels and booking a trip
    * Only logged in user can access his trip history, profile updation and other features.

  
<!-- ============================================  TECH STACK ======================================================  -->

## Tech Stack

* Java
* Spring Framework
* Spring Boot
* Spring Data JPA
* Hibernate
* Maven
* MySQL

<!-- ============================================  MODULES ======================================================  -->

## Modules

* Login, Logout Module
* Packages Module
* Booking Module
* TicketDetails Module
* Route Module
* Travels Module
* Bus Module
* Hotel Module
* Report Module
* Feedback Module

<!-- ============================================  ER - DIAGRAM ======================================================  -->

# ER Diagram

The following Diagram depicts the flow of our Entity Relation Diagram to simplify the work flow.
<br>
<br>
  
 <img src='https://user-images.githubusercontent.com/101464018/201532557-608c199c-53cb-4b82-91d6-a5313da04eef.png'/>


<br>
<br>

<!-- ============================================  INSTALLATION AND RUN ======================================================  -->

## Installation & Run

* Before running the API server, you should update the database config inside the [application.properties](TourNestTripManagementSystemApplication/src/main/resources/application.properties) file. 
* Update the port number, username and password as per your local database config.

```
    server.port=8888

    spring.datasource.url=jdbc:mysql://localhost:3306/mydb;
    spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
    spring.datasource.username=root
    spring.datasource.password=root

```

<!-- ============================================  API ROOT ENDPOINTS ======================================================  -->

## API Root Endpoint

`http://localhost:8888/`

`http://localhost:8888/swagger-ui/`
