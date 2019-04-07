# Game It Up

🚀 Deployed at: https://gameitup.herokuapp.com

Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

Installation
Please clone and download this folder to your hard disk. You will then navigate to the folder and run npm install or yarn. This will install the cookie-session, dotenv, express, express-handlebars, geolib, keys, mysql2, passport, passport-google-oauth20, and sequelize dependencies.

Update the PORT settings in express if necessary, and type node server to get your personal server running. Open your favorite browser and visit localhost:xxxx in your browser where xxxx will be your port number.

Data Persistence
Ensure that you have a MySQL database server running locally for data peristance. You will also need to include your keys in a .env file.

Functionality
Overall Applications Concept
Users can log into the application via a gmail account. From there, users can do one of the following: Create a game or find a game. If a user wants to create a game, they would click on the create game button and fill out the form for that. In contrast, if they wanted to find a game, they can fill out the form and meet up locations will appear on the google map.

Motivation for development
We wanted to created an application where it would be easy to meet new people, and connect them through recreation pick up games. Sometimes it can get a bit difficult organizing pick up games, and sometimes it’s difficult finding people. We are helping that our application can help ease those things.

Design Process
We wanted to make the application “easy-to-use”. We decided to create two big buttons on the home page. Each button will either take the user to the find game page or the create game page. From there, we created a form to gather information from the user: type of sport, date, time, etc.
<br>
Built With
HTML/CSS
JavaScript
SQL
Google Maps API
Handlebars
Node.JS
Passport
Google OAuth

Authors:
- Joel Fecke
- Harpal Assi
- Phi Tran
- Markie Ruiz
