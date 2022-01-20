# Cinema App
![cinema logo](https://cdn.thespaces.com/wp-content/uploads/2018/07/delphiluxartboard_2q_.jpg)

### General info
This project simulates cinema ticket shop with simple authentication system based on Hibernate and Spring 

### Application functionality
```
- User authentication and authorization
- Adding new movie, cinema hall, movie session
- Creating order
- Display all the above information
```

### Endpoints
*Available endpoints in the project:*
* POST: /register - all
* GET: /cinema-halls - user/admin
* POST: /cinema-halls - admin
* GET: /movies - user/admin
* POST: /movies - admin
* GET: /movie-sessions/available - user/admin
* POST: /movie-sessions - admin
* PUT: /movie-sessions/{id} - admin
* DELETE: /movie-sessions/{id} - admin
* GET: /orders - user
* POST: /orders/complete - user
* PUT: /shopping-carts/movie-sessions - user
* GET: /shopping-carts/by-user - user
* GET: /users/by-email - admin

### Technologies
*The following stack of technologies was used in the project:*
* Tomcat
* Hibernate
* Spring Web
* Spring Security
* Spring Core
* MySQL
* Maven checkstyle plugin

### Setup
*Step-by-step project launch information:*
```
- Install IntelliJ IDEA Ultimate and Tomcat 9.0.50
- Install MySQL and MySQL Workbench
- Clone this project
- Configure Tomcat Server and create a schema in MySQL
- Insert your DB properties in the resources/db.properties
- After that you can run the application and login using:
    * username `admin@gmail.com` and password `admin` for login as admin
    * username `alice@gmail.com` and password `alice` for login as user
```
