<!--Title-->
# MovieDatabase
<!--Content Table-->
## Content
- [MovieDatabase](#stars-university) <!--Link to the title of the project-->
  * [Purpose](#purpose) <!--Link to the purpose of the project-->
  * [Description](#description) <!--Link to the description of the project-->
  * [Classes](#classes) <!--Link to the classes of the project-->
    + [UML](#UML)<!--Link to the UML of the project-->
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
This poject is a Movie database. The purpose of this project is to build a java application to display a list of movies and providing more information on the movies.

<!--Header 2 description of the project-->
## Description

The project is a java application program divided into multiple class. The program start by displaying a login page in case that the user does not have an account he/she can signup and a new account obejct will be created and the user data will be saved in the database. Afterwards a home page will display all the movies when a user clicks on one of them he/she will get more info about the movie director, description, etc. Lastly, the user can view the movie rating and update it. Other freatures exists in the classs but are not implemented in the GUI, as follows:
* If a user is created as an admin he can add and delete movies and users. 
* We also have an action classes that enables the user to preform actions related to the movies such as reviewing the movie, or display the characters, directors etc. of a particular movie or display the movies of a prticular director etc.
* Lastly we have a driver class called Movie whcih creates movie objects with the needed movie information.
* The subclass of MovieEcosytem which are actor, director etc contain information related to the actors, directors etc.

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

### Dependencies

<!--Link to install the latest version of g++-->
* You will need to have the latest version of g++ to run the program. g++ 8.1.0 (MinGW), a link is provided.
* [g++ 8.1.0 (MinGW)](https://sourceforge.net/projects/mingw-w64/files/Toolchains%20targetting%20Win32/Personal%20Builds/mingw-builds/installer/mingw-w64-install.exe/download)

### Installing
<!--Steps of Installation-->
* Download the java version 17.0.1. 
* Download the zip file and create a folder for it.
* Add

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
