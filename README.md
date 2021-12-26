<!--Title-->
# Stars University 
<!--Content Table-->
## Content
- [Stars University](#stars-university) <!--Link to the title of the project-->
  * [Purpose](#purpose) <!--Link to the purpose of the project-->
  * [Description](#description) <!--Link to the description of the project-->
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
This poject is a Stars University database. The purpose of this project is to build a menu driven program using multiple class to display the Stars University database information. 

<!--Header 2 description of the project-->
## Description

The project is a menu driven program divided into multiple class. The program should display the menu and asks the user to choose whether to display the student information extrated from the Student class and DynArray class, or display the course information using the Course and StatArray class, display the Taken objects which are the information of a course taken by a particular student the program uses the Taken and School class to diplay the information. Finally, the user can add a Taken object using the DynArray class. The flow of the project is implemented in the Control class and the View is used to display the menu.

<!-- Files of the project-->
## Files

### Header Files

* Control.h
* Course.h
* DynArray.h
* School.h
* StatArray.h
* Student.h
* Taken.h
* View.h

### Source Files

* Control.cc
* Course.cc
* DynArray.cc
* School.cc
* StatArray.cc
* Student.cc
* Taken.cc
* View.cc
* ProjectTestDriver.cc

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
* Aicha Sidiya-S20106146
* Hanin Alzaher-S20106145
* Lamr Aljahdali-S20106219
* Joud Kaki-S20106234


## Acknowledgments
<!-- Insparation files, codes, and general refrences used in writing the code of the project-->
* Book - C++ Programming. Program Design including Data Structures by D.S. Malik
* StatArray.h
* [Dynamic Array](https://www2.cs.sfu.ca/CourseCentral/225/johnwill/lab_arrays_intro.html)
* [C++ Pre-processor](https://doc.bccnsoft.com/docs/cppreference_en/preprocessor/all.html)
* [C++ documentation](https://www.cplusplus.com/doc/)
* [Readme Template](https://gist.github.com/DomPizzie/7a5ff55ffa9081f2de27c315f5018afc)
