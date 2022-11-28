# 🎬 Cinema-Service 🎬

### 🌌 Project description:
```
This is simple simulator of cinema service for reservation tickets, that supports registration, 
authentication and CRUD operations. This service allows you to save/delete/update data about 
the movie hall, movie session, movies, users who have a role, your basket in which orders with 
tickets can be stored.
```

## 🎯 Features:
* register or login as user
* create and find movies
* create and find available movie sessions
* creating shopping cart
* add tickets to shopping cart
* complete an order

## ⭐ Technologies used:
* Java 11
* MySql
* Hibernate
* Maven
* Tomcat 9.0.64
* Java Servlet API
* Spring Framework

## 📜 Project architecture:
The Cinema-Service is based on 3-layer architecture:
1. Controllers, which handle requests, call services and send responses
2. Services - there are all business logic
3. DAO, which handle CRUD operations to database

## ⚙️ Installation:
1. Install the project to your computer using the link.
2. Go to the file `src/main/resources/db.properties` and replace the variables with your data to connect to the database.
3. And now you can run the code through tomcat server.
