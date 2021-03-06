#Kalah Game

A web application that runs the game of 6-stone Kalah. 
For the general rules of the game please refer to Wikipedia: https://en.wikipedia.org/wiki/Kalah. 
This is a Java based project using Maven for building and managing.

##Project's structure

This project consists of two parts:

1.The back end which is responsible for the whole game process and implements all the rules of the game.
It is implemented on Java. For the communication with the front-end I used RESTful Web Services which were
built with JAX-RS and Jersey API.

2.The front end which is responsible only for taking the user's input, sending it to the server, 
receiving back the updated board of the game and appear it on the browser. It was implemented with AngularJS.

##Usage

In order to run the application you need Java 8 and Tomcat 7+.

 Clone the repository from Github:

$ git clone git://github.com/stavpap/kalah.git

 Navigate into the cloned repository directory

$ cd kalah

 The project uses Maven to build

$ mvn clean install

 Launch Tomcat and deploy the war file to it. The target folder with the build and war files is included in the repository.
So for your convenience you can go to this step immediately after cloning the repository

 Access the deployed webapp at

http://localhost:8080/kalah

#Screenshots

![Image of kalahWelcome](http://s13.postimg.org/7b6w5jcvr/kalah_Welcome.png)
 
![Image of kalahPlay] (http://s7.postimg.org/5pg1sk3gb/kalah_Play.png)

![Image of kalahEnd] (http://s27.postimg.org/vroqfgo1v/kalah_End.png)
