---
layout: project
type: project
image: images/carpoolLogo.jpeg
title: Carpool-And-Go
permalink: projects/carpoolNGo
# All dates must be YYYY-MM-DD format!
date: 2022-05-09
labels:
  - Javascript
  - Meteor
  - MongoDB
  - GitHub
summary: A website to give UH students the ability to connect with others interested in carpooling to various places around the island. Both riders and drivers may seek out each other by location and time.
projecturl: https://hnlcory.github.io/projects/carpoolNGo
---
<div style="overflow: auto; max-height: 80vh; background-color: #ffffffb0; padding-left: 10px; padding-right: 10px; padding-top: 8px;">
  
<img class="ui medium right floated rounded image" src="https://hnlcory.github.io/images/bankDB.png" alt="Image">

The Bank Database project is intended to be an application used by bank staff which can store the information of their clients. The command prompt is utilized to interact with the system while the storage, addition, search, and deletion of customer records are handled by the database.<br><br>

This project was created within the UH Unix system, utilizing the C++ platform. Data is stored within a structure called record shown below.

<pre>
  <code>
struct record
{
    int                accountno;
    char               name[25];
    char               address[50];
    struct record*     next;
};
</code>
</pre>

These records allow the database to store information using a linked list. Through extensive testing, the application is able to store a wide range of information as well as proper error handling, and debug options within the application. Information can be both read in, and stored inside .txt files allowing for data to be saved when the user exits the program.<br><br>
  
This project was initially designed in C to focus on the use of Pointers in order to pass or reference data. As a follow-up project after familiarizing with the differences in C++, this application’s database was redesigned to utilize the advantages of C++ such as strings, passing by reference, and text outputting differences. The User Interface was also slightly modified to conform to these new changes.<br><br>
  
Makefile is also utilized to easily generate public, and debug builds of the application. The full project is on display at the link below.<br><br>

Source: <a href="https://carpool-and-go.github.io/"><i class="large github icon"></i>CarpoolNGo</a>
</div>
