# CINEMA-APP
________________
## Description:
Web application for buying movie tickets. Make order on a movie session in a particular cinema hall and just put it in your shopping cart. The app wrote according to all SOLID principles and supported all CRUD operations.
______________
## Features:
### for User:
+ Registration
+ Get all cinema halls
+ Get all movies
+ Get all movie sessions
+ Get my orders
+ Complete my orders
+ Add movie session to shopping cart
+ Get my shopping carts
### for Admin:
+ Add cinema halls
+ Add movies
+ Add, Update, Delete movie sessions
+ Get all users
____________
## Available endpoints:
+ POST: /register - all
+ GET: /cinema-halls - user/admin
+ POST: /cinema-halls - admin
+ GET: /movies - user/admin
+ POST: /movies - admin
+ GET: /movie-sessions/available - user/admin
+ POST: /movie-sessions - admin
+ PUT: /movie-sessions/{id} - admin
+ DELETE: /movie-sessions/{id} - admin
+ GET: /orders - user
+ POST: /orders/complete - user
+ PUT: /shopping-carts/movie-sessions - user
+ GET: /shopping-carts/by-user - user
+ GET: /users/by-email - admin
______________
## Technologies:
+ JDK 11
+ Maven 4.0.0
+ MySQL 8.0.22
+ TomCat 9.0.70
+ Spring security 5.6.10
+ Spring Web 5.3.20
+ Spring 5.3.20
+ Jackson databind 2.14.1
+ Json 20220924
+ Hibernate 5.6.14
_______________
## Start the program:
+ Install JDK
+ Install Tomcat server
+ Clone the project from GitHub
+ Configure db.properties file
+ Configure Tomcat server
+ Use Postman to test the program
+ At the start created default admin with login: admin@i.ua password: admin123
