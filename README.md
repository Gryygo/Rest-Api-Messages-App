# REST API for a React feed messages app

### This application was created as a study project for the *Node.js - The Complete Guide* course on Udemy and can be accessed *[here](https://restapi-messages.netlify.app)*

This app utilizes the following technologies:
  - Express framework
  - MongoDB for noSQL database, with the proper implementation in node being made through the mongoose ODM
  - Express-validator for server side validation in every form
  - Bcrypt package for encrypting personal data (the user's password in this case)
  - Multer for handling the uploaded images (initialy, the app utilized URL for the images, but was changed to uploaded files for better data control)
  - Json webtoken for better handling the website authentication
  - Socket.io for websocket's implementation

Really fun and enlightening project to work on.I did this project right after finishing the [server side rendering shop app](https://github.com/Gryygo/NodeCourse-ShopApp) and was quite relaxing actually. Getting to focus more on the backend made the whole
process more easy to understand. This wasn't my first experience with REST APIs (since i already had some contact with Django and Django REST) so grasping the concepts was quite simple and so was the actual implementation.
In this project i was also able to understand better websockets (through socket.io) and see how handy this can be. I used it to establish a live connection between users, so anyone would be able to see in real time if any post was added, edited or deleted. However, this was just a basic use of websockets and i plan 
in using it in some kind of message application in near future to really master this tool.

### Some challenges in this project:
 
Unlike my last project, this one was really smooth and i barely had any issues. I still had some trouble doing the api's connection with the React app, but it really was more of a "little experience with React" problem than a "APIs are hard" problem.
In the API itself everything was really nice and clean. Even so, i think i still have lots to learn about REST APIs and i'm already thinking in a bunch of projects to exercise it. I'm also planning to go back to studying React
in the next weeks, so probably i will have lot less troubles in the next fullstack projects. Right now i'm working in some personal projects with server side rendering and more "backend focused", so i think React still have to wait a bit.
