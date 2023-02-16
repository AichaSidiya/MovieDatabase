<!--Title-->
# MovieDatabase
<!--Content Table-->
## Content
- [MovieDatabase](#stars-university) <!--Link to the title of the project-->
  * [Purpose](#purpose) <!--Link to the purpose of the project-->
  * [Description](#description) <!--Link to the description of the project-->
  * [Features](#features) <!--Link to the description of the project-->
  * [Classes](#classes) <!--Link to the classes of the project-->
    + [UML](#UML)<!--Link to the UML of the project-->
  * [Getting Started](#getting-started) <!--Link to the steps for launching the project-->
    + [Installing](#installing) <!--Link to Installation-->
    + [Executing program](#executing-program) <!--Link to Execution-->
      - [How to run the program](#how-to-run-the-program) <!--Link to the steps for launching the project-->
  * [Build With](#build-with) <!--Link to the Contributors of the project-->
  * [Authors](#authors) <!--Link to the Contributors of the project-->
  * [Acknowledgments](#acknowledgments) <!--Link to the Acknowlegments-->

## Purpose
<!--Purpose of the project-->
This poject is a Movie database. The purpose of this project is to build a java application to display a list of movies and providing more information on the movies.

![alt text](https://github.com/AichaSidiya/MovieDatabase/blob/main/demoMovie.gif)

<!--Header 2 description of the project-->
## Description

The project is a java application program divided into multiple class. The program start by displaying a login page in case that the user does not have an account he/she can signup and a new account obejct will be created and the user data will be saved in the database. Afterwards a home page will display all the movies when a user clicks on one of them he/she will get more info about the movie director, description, etc. Lastly, the user can view the movie rating and update it. Other freatures exists in the classs but are not implemented in the GUI, as follows:
* If a user is created as an admin he can add and delete movies and users. 
* We also have an action classes that enables the user to preform actions related to the movies such as reviewing the movie, or display the characters, directors etc. of a particular movie or display the movies of a prticular director etc.
* Lastly we have a driver class called Movie whcih creates movie objects with the needed movie information.
* The subclass of MovieEcosytem which are actor, director etc contain information related to the actors, directors etc.

## Features
* View a list of movies
* Create/Delete account
* Add a new movie
* Rate an existing movie
* Database integration using XAMPP

<!-- Files of the project-->
## Classes
- Abstract class: Person
- Account
  + Admin
  + User
- MovieEcosystem
  + Actor
  + Director
  + Writer
  + Producer
- Action
  + Reviews
  + Acts
  + Writes
  + Produces
- Movie
### UML 


![UML drawio](https://user-images.githubusercontent.com/91727165/180050404-f86eb84e-53b9-4647-8b3d-17d4c27a158a.png)

<!--Header 3 installation and launching the project-->
## Getting Started

### Installing
<!--Steps of Installation-->
* Download the java version 17.0.1. 
* Download the zip file and create a folder for it.
* Add the sql table to phpmyadmin.
* download Eclipse

### Executing program
<!--Steps for running the program-->
#### How to run the program

* Look for signIn.java and run it and you can then run your program.

## Built With

- [Java](https://www.java.com/) - Programming language
- [Swing](https://docs.oracle.com/en/java/javase/14/docs/api/javax/swing/package-summary.html) - Framework for creating graphical user interfaces
- [XAMPP](https://www.apachefriends.org/index.html) - A software stack that includes Apache, MariaDB, and PHP

## Authors
<!-- The contributors to the project-->
* [Aicha Sidiya](https://github.com/AichaSidiya)
* [Hanin Alzaher](https://github.com/hanin-az)
* [Reem Alsharbi](https://github.com/ReemAlsharabi)
* Alanoud Alhutami


## Acknowledgments
<!-- Insparation files, codes, and general refrences used in writing the code of the project-->
* [Readme Template](https://gist.github.com/DomPizzie/7a5ff55ffa9081f2de27c315f5018afc)
* [IMBD example](https://uwe.pst.ifi.lmu.de/exampleIMDB.html)
* [Java GUI](https://youtu.be/clKDMtfNNuo)
* [PHP and Java](https://youtu.be/h40mEf7WyMQ)
* [JFrames](https://youtu.be/3dlvseTkRHg)
