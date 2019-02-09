# Group Project #2 

The Interstellar Universe ------ [Check out our application!]() 

Team Members --- [Dan](https://github.com/DanRSolomon), [Kieran](https://github.com/LopTwo), [Jennifer](https://github.com/alejosjen), [Melissa](https://github.com/melperez19)

Project Description --- A learning platform based on space data in which users can select specific topics to explore. The home page will display
                        space and georgraphical data based on the user's location and allow them the opportunity to take a space quiz on a seperate
                        page, in which they will be added to the database of users who have completed the quiz as well.

---------------------------------------------------------------------------------------------------------------------------------------------------

Final application screesnshot -

![final-screenshot](https://github.com/alejosjen/groupProject2/blob/master/public/assets/images/proj2screenshot.png) 
![final-screenshot](https://github.com/alejosjen/groupProject2/blob/master/public/assets/images/quizScreenshot.png)

-- created by Team Funtastic 4

---------------------------------------------------------------------------------------------------------------------------------------------------
APIs and Technologies used
* Anime.js - using Timeline, Melissa developed our moving letters to capture attention
* Ebay API - tailored to pull only from the Science & Education category
* OpenWeather API - to pull weather data based on location
* NASA APOD API - to provide NASA's 'Image of the Day' with description
* Weather API - based on location input
* spaceDB - created API Get and Post requests to our own MySQL database for the quiz page of the app
* Live Space Station Tracking Map & The Spot The Station widget - shows where the Space Station is right now lets you display ISS  
  sighting opportunities based on exact location. 

----------------------------------------------------------------------------------------------------------------------------------------
To USE: 
* Dependencies: Axios, dotenv, express, mysql, mysql2, path, sequelize
* DevDependencies: chai, chai-http, cross-env, eslint, mocha, prettier
* We used yarn, npm installs, and travis to help our team install and check work

Future Developments:
* Add resources for our learners to investigate the quiz questions
* Setup a community of learners who can suggest new questions
* Develop categories of quizzes that grow with our learners, as their interests and questions change so will our site to reflect their needs and curiosities
----------------------------------------------------------------------------------------------------------------------------------------

Highlights

* We're using Node and Express as our server

* We built a database in MySQL for the quiz questions and then utilized Sequelize to build the tables

* GET routes were created with all API's and POST routes to our database adds on new user information

* Our site is deployed with Heroku. It runs our Sequelize code to generate our quiz page with questions seeded from our database.

* Our front end uses HTML5, CSS3, Javascript, and JQuery, axios, express, path, and sequelize. 

* Our front and back end uses the MVC model. Our models join our HTML paths with sequelize and dynamically create our database tables to run on our local server. Our views were hand coded and styled with HTML5, CSS5, and Javascript. Our controllers are in the routes folder with directs client-side traffic to the right places and returns the requested information like pages, quiz questions, and API calls.

* For security we utilized dotenv to keep our API keys safe. For input validation our server-side uses sequelize to check input and compare if a username is already taken.
