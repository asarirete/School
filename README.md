<!--Title-->
# Advanced Programming Project
<!--Content Table-->
## Content

  * [Purpose](#purpose) <!--Link to the purpose of the project-->
  * [Description](#Description) <!--Link to the description of the project-->
  * [Files](#files) <!--Link to the description of the project-->
    + [Header Files](#header-files) <!--Link to Dependencies-->
    + [Source Files](#source-files) <!--Link to Installation-->
  * [Getting Started](#getting-started) <!--Link to the steps for launching the project-->
    + [Dependencies](#dependencies) <!--Link to Dependencies-->
    + [Installing](#installing) <!--Link to Installation-->
    + [Executing program](#executing-program) <!--Link to Execution-->
      - [How to run the program](#how-to-run-the-program) <!--Link to the steps for launching the project-->
    + [Help](#help) <!--Link to Execution-->
  * [Authors](#authors) <!--Link to the Contributors of the project-->
  * [License](#license) <!--Link to the Liscence of the project-->
  * [Acknowledgments](#acknowledgments) <!--Link to the Acknowlegments-->

## Purpose
<!--Purpose of the project-->
For this project, our goal is to write a C++ program to manage the data for a school with students and courses. We will implement a program using objects from the different classes, based on a UML class diagram provided for us.

<!--Header 2 description of the project-->
## Description

The project is a menu-driven software with several classes. The software should provide a choice and prompt the user to select (one of the six choices).      
0) Exit is just for terminating the execution of the function immediately.  
1) Display the student information extracted from the student class and DynArray class.                         
2) Display the course information extracted from the course class and statArray class.            
3) The Taken class is used by the software to show all the courses Taken.   
4) The program uses the taken class to represent the details of a course taken by a certain student.           
5) The user may utilize the statArray class to add (course taken by student) a Taken object.


<!-- Files of the project-->
## Files

##### Header Files

* Control.h
* View.h
* Student.h
* Course.h
* Taken.h
* DynArray.h
* StatArray.h
* School.h



##### Source Files

* Control.cc
* View.cc
* Course.cc
* Student.cc
* Taken.cc
* DynArray.cc
* StatArray.cc
* School.cc
* TestDriver.cc

<!--Header 3 installation and launching the project-->
# Getting Started

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
###### How to run the program
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
to remove object and executable files.

## Authors
<!-- The contributors to the project-->
* Alanood Alhuttami - S20106728
* Layal Alsilani - S20106801
* Layan Jaman - S20106590
* Hajar Abbas - S20106427


## Acknowledgments
<!-- Insparation files, codes, and general refrences used in writing the code of the project-->
* Book - C++ Programming. Program Design including Data Structures by D.S. Malik
* StatArray.h
* [Dynamic Array](https://www2.cs.sfu.ca/CourseCentral/225/johnwill/lab_arrays_intro.html)
* [C++ Pre-processor](https://doc.bccnsoft.com/docs/cppreference_en/preprocessor/all.html)
* [C++ documentation](https://www.cplusplus.com/doc/)
* [Readme Template](https://gist.github.com/DomPizzie/7a5ff55ffa9081f2de27c315f5018afc)
* [Markdown License badges](https://gist.github.com/lukas-h/2a5d00690736b4c3a7ba)
