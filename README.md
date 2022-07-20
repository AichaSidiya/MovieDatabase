<!--Title-->
# MovieDatabase
<!--Content Table-->
## Content
- [MovieDatabase](#stars-university) <!--Link to the title of the project-->
  * [Purpose](#purpose) <!--Link to the purpose of the project-->
  * [Description](#description) <!--Link to the description of the project-->
  * [Classes](#files) <!--Link to the description of the project-->
  * [Getting Started](#getting-started) <!--Link to the steps for launching the project-->
    + [Dependencies](#dependencies) <!--Link to Dependencies-->
    + [Installing](#installing) <!--Link to Installation-->
    + [Executing program](#executing-program) <!--Link to Execution-->
      - [How to run the program](#how-to-run-the-program) <!--Link to the steps for launching the project-->
    + [Help](#help) <!--Link to Execution-->
  * [Authors](#authors) <!--Link to the Contributors of the project-->
  * [Acknowledgments](#acknowledgments) <!--Link to the Acknowlegments-->

## Purpose
<!--Purpose of the project-->
This poject is a Movie database. The purpose of this project is to build a java application with its gui displaying a list of movies and providing more information on the movies if the user clicks on a movie he/she wish to read about. The program starts by asking the user to either login or create an account to be able to browse the database.

<!--Header 2 description of the project-->
## Description
First of all we started by creating the class related to the user such as: Person, Account, Admin, and User. The Person class is an abstract class playing the role of a general template for any instance that has a name and a birth date. Then, the account class which is a subclass of Person contained the credentials of a user such as email, username, and password. Lastly we created an admin and a user whom both were subclasses of Account. The main difference between the two is that the admin could add and delete movies and users.
Then we worked on the MovieEcosystem which is a subclass of Person and had 4 subclasses constituting the different people who work on a movie such as actors, directors, producers, and writers. We included information about each of them, their birth place and their awards.
To be able to link the movie to the user and to link all classes together we created an action superclass which contained methods that would display characters of a particular movie or display movies by a particular director, actor, producer etc. The action class also displayed the reviews for each movie. Action class has multiple subclass including review, acts, produces, and writes which helped us to build relations between user and movie, or writer and movie while also providing some attribute for this relation such as role for acts.
Action class has methods to display all the movies that has a relation with a particular person and vice versa. For example, the method displayAllPersons takes a Movie object as a parameter and prints all of the actors, producers etc. The Acts class has a method called displayAllCharacters, which takes a Movies object as a parameter and prints all the characters names in this movie. Also, the User class has the methods ChangeUserName and ChangePassword, they allow the user to change his/her username and password.
Lastly, we created a movie class which included information specific to the movie such as title, genre, showDate, description, and quote. The class also included a director ArrayList to create a connection between director and movie, because the director dosen’t have any particular role like actor so we felt that a directs class under Action was not needed.
<!-- Files of the project-->
## Classes
Inheritance: Actor, Writer, Director and Producer are subclasses of MovieEcosystem.
Polymorphism: Action class.
Overriding methods: toString method.
Overloading methods: overloaded constructors.
Abstract classes: Person class.
Exceptions: setName method in Person class, setEmail method in Account class.
Regular expressions: in the setters of the Account class.

<!--Header 3 installation and launching the project-->
## Getting Started

### Dependencies

<!--Link to install the latest version of g++-->
* You will need to have the latest version of g++ to run the program. g++ 8.1.0 (MinGW), a link is provided.
* [g++ 8.1.0 (MinGW)](https://sourceforge.net/projects/mingw-w64/files/Toolchains%20targetting%20Win32/Personal%20Builds/mingw-builds/installer/mingw-w64-install.exe/download)

### Installing
<!--Steps of Installation-->
* Download the g++ compiler and intall it. 
* Download the zip file and create a folder for it.

### Executing program
<!--Steps for running the program-->
#### How to run the program
* Look for Run Terminal in your search bar
* Open it and use the:
<!--commands to run the program "cd" change directory to where your files are-->
```
cd 
```
command to go to the specified directory.
* Use
<!--commands to run the program "make project" compile the program--> 
```
make project 
```
to compile the all the project files.
* Than type 
<!--commands to run the program "project" run and executes program-->
```
project 
```
to execute and run the program.

### Help
If the code does not compile use 
<!--commands to remove object and excevutable files "project"-->
```
make clean
```
to remove object and excevutable files.

## Authors
<!-- The contributors to the project-->
* Aicha Sidiya
* Hanin Alzaher
* Reem Alsharbi
* Alanoud Alhutami


## Acknowledgments
<!-- Insparation files, codes, and general refrences used in writing the code of the project-->
* Book - C++ Programming. Program Design including Data Structures by D.S. Malik
* StatArray.h
* [Dynamic Array](https://www2.cs.sfu.ca/CourseCentral/225/johnwill/lab_arrays_intro.html)
* [C++ Pre-processor](https://doc.bccnsoft.com/docs/cppreference_en/preprocessor/all.html)
* [C++ documentation](https://www.cplusplus.com/doc/)
* [Readme Template](https://gist.github.com/DomPizzie/7a5ff55ffa9081f2de27c315f5018afc)
