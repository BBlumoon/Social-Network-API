# Social-Network-API

## Description
This application is a social network api where users can create their own profiles with a username and email. Users can then create their own thoughts and reactions and also add friends by using a unique user id. 

## Usage
Use npm start to begin the application. MongoDB and Mongoose are used to see thought and user data. Insomnia will be used to create the seed data as well as test the api routes that are used.

## Technologies Used
Javascript
MongoDB
Mongoose
Express.js
Node.js
Moment.js
Insomnia

## Acceptance Criteria
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list