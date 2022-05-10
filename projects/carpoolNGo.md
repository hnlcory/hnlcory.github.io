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

<p>
Carpool-and-Go is a web application project that aims to provide a communal network for University of Hawaii at Manoa, allowing for drivers to offer rides, and for riders to be able to search for drivers in their area. The goal of the project is take in what we have learned over the course of the semester to create a functioning meteor application that reflects teachings of the ICS 314 - Software Engineering course while providing exposure to Software development when a group scenario is given. 
</p>

<p>
This project was created using the Meteor framework in order to develop a Full-Stack Javascript application. The project is build on Javascript with MongoDB handling the database. UI components are developed with Semantic UI utilizing the official React integration. Testing for the application is automated via Test Café tests, and coding standards/error management are maintained via ESLint. Currently, the main build is deployed via Digital Ocean, and can be visited <a href="https://uh-carpool-and-go.xyz/#/">here</a>. 
</p>
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
