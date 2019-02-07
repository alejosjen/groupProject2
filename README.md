# Group Project #2 

The Interstellar Universe ------ [Check out our application!]() 

Team Members --- [Dan](https://github.com/DanRSolomon), [Kieran](https://github.com/LopTwo), [Jennifer](https://github.com/alejosjen), [Melissa](https://github.com/melperez19)

Project Description --- A learning platform based on space data in which users can select specific topics to explore. The home page will display
                        space and georgraphical data based on the user's location and allow them the opportunity to take a space quiz on a seperate
                        page, in which they will be added to the database of users who have completed the quiz as well.

---------------------------------------------------------------------------------------------------------------------------------------------------
Sketch of final product - 

![layout-image]() 

-- created by Team Member...

---------------------------------------------------------------------------------------------------------------------------------------------------

Final application screesnshot -

![final-screenshot](https://github.com/alejosjen/groupProject2/blob/master/public/assets/images/proj2screenshot.png) 
![final-screenshot](https://github.com/alejosjen/groupProject2/blob/master/public/assets/images/quizScreenshot.png)

-- created by Team Funtastic 4

---------------------------------------------------------------------------------------------------------------------------------------------------
APIs and Technologies used

* OpenWeather API - to pull weather data based on location
* NASA APOD API - to provide NASA's 'Image of the Day' with description
* Weather API - based on location input
* spaceDB - created API Get and Post requests to our own MySQL database for the quiz page of the app
* Live Space Station Tracking Map & The Spot The Station widget - shows where the Space Station is right now lets you display ISS  
  sighting opportunities based on exact location. 
----------------------------------------------------------------------------------------------------------------------------------------

Rough Breakdown of Tasks

* Use a Node and Express Web Server; 
  Done

* Be backed by a MySQL Database an ORM (not necessarily Sequelize); 
  Done with spaceDB

* Have both GET and POST routes for retrieving and adding new data; 
  Get routes were created with all API's and Post routes to the spaceDB adds on new user information

* Be deployed using Heroku (with Data);

* Have a polished frontend / UI;
  Done

* Have folder structure that meets MVC Paradigm;
  Done

* Meet good quality coding standards (indentation, scoping, naming).
  Done

* Must not expose sensitive API key information on the server, see [Protecting-API-Keys-In-Node.md](../../../10-nodejs/Supplemental/Protecting-API-Keys-In-Node.md)
Utilized process.env in numerous areas to keep our API keys safe

* Use a new library that hasn't been discussed in class
  We chose to Animate.js, which is a javascript library that allows various types of animations to execute on your page.
  We created Moving Letters for our Page Headers using Animate.js.

