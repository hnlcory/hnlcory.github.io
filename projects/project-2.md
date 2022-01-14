---
layout: project
type: project
image: images/bankDB.png
title: Banking Database Application
permalink: projects/BankDB
# All dates must be YYYY-MM-DD format!
date: 2021-11-09
labels:
  - C++
  - GitHub
summary: An application to manage customer's bank records stored in their database
projecturl: https://hnlcory.github.io/projects/BankDB
---
<div style="overflow: auto; max-height: 100vh; background-color: #ffffffb0;">
  
<img class="ui medium right floated rounded image" src="https://hnlcory.github.io/images/bankDB.png">

<br>The Bank Database project is intended to be an application used by bank staff which can store the information of their clients. The command prompt is utilized to interact with the system while the storage, addition, search, and deletion of customer records are handled by the database.<br><br>

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
Makefile is also utilized to easily generate public, and debug builds of the application. The full project is on display at the link below.<br><br>

Source: <a href="https://github.com/hnlcory/ICS212/tree/main/project2"><i class="large github icon"></i>BankingDatabase</a>
</div>
