# Supperwhere

Supperwhere is an application that allows users to figure out dining recommendations based on their dietary preferences and meal history. The app will help locate restaurants for the user based on those preferences. The application aims for making the dining experience more convenient for the user by providing quick and easy options for them to use to tailor their preferences. 

## History

The idea for Supperwhere comes from a commonly recurring dillema: What do I eat for dinner? The decision making process for what to get for dinner can be a huge time-sink, and often times leaving the decision to chance can result in regret or second guesses. The idea for supperware was to use data to justify an optimal dinner decision, rather than just a random suggestion, or flipping a coin.

## Prototype

The following is a link to a prototype for what the application was originally planned to look like:
https://projects.invisionapp.com/share/MGW6PTTJ4HP#/screens/407491823_Login_Page

## Link

http://supperwhere.herokuapp.com/

## Running the App (If above link is down)

1. Make sure that you have .env present in the app/back-end folder; the app will not start without it. The .env sets environment variables for "DB_CONN" (a connection string variable to a mongodb database), "ZOMATO_API_KEY" (an API key for the zomato API), and "TOKEN_SECRET" (a secret string used for authentication).
2. cd into the front-end folder (app/front-end) from the app directory. Input "npm install" to make sure you have all the dependencies on that folder. Then input and run "npm start" to start the react portion of the app, which will send you to the homepage.
3. cd back to the back-end folder (app/back-end) from the app directory.
5. Run "npm install" on the back-end folder to be safe in terms of having all the dependencies for express and Zomato.
6. Once that's set up, do "npx nodemon" from the back-end folder to start the server, and you're all set.
