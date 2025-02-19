<<<<<<< HEAD
# Course-Registration-System-
This project is a Java-based web application built using the Spring Framework.
=======
# Course

Course registration project using Java Web with Spring Framework.<br>
Spring much lighter! :)

## Features

- CRUD
- ACL
- Validation
- Login
- Responsive

## Requirements

- NetBeans 8.2
- Java JDK 1.8
- Apache Tomcat >= 9
- MySql >=5

## Tecnologies

- Java
- JPA
- Maven
- Spring
- CSS
- Bootstrap
- MySql

## Installation

```
$ git clone https://github.com/iamprish121/Course-Registration-System-.git

$ cd spring-course

```

Then create a database with name spring_course in your mysql. You can find database dump in spring_course.sql, import it:

```
$ mysql -u <your user> -p <your password>

mysql> create database `spring_course`;

mysql> use `spring_course`;

mysql> source spring_course.sql

```

Then open the file "src/main/resources/application.properties" and enter the data according to the connection of your database. <br>

When the configuration is complete, just type in the terminal "mvn spring-boot: run" and open in your browser the following address: <br>

http://localhost:8080/

## Demonstration


- Login
    - Username: admin
    - Password: admin

## Licence

User Registration is licensed under <a href="LICENSE">The Apache License (Apache)</a>.

## Screenshots

![Screenshots](screenshots/screenshot01.png)<br><br>
![Screenshots](screenshots/screenshot02.png)<br><br>
![Screenshots](screenshots/screenshot03.png)<br><br>
![Screenshots](screenshots/screenshot04.png)<br><br>
![Screenshots](screenshots/screenshot05.png)<br><br>
![Screenshots](screenshots/screenshot06.png)<br><br>
![Screenshots](screenshots/screenshot07.png)<br><br>
![Screenshots](screenshots/screenshot08.png)<br><br>

## Model ER

![Screenshots](model_er.png)<br><br>


Developed by<br>
Priyanshu Anand<br>
Priyanshua038@gmail.com<br>
https://github.com/iamprish121<br>
>>>>>>> b499e91 (Initial commit)
