# Goalsetter Backend


## How to run the server?
1. clone this repo
2. install dependencies via npm from the root directory. Follow the instructions
  a. npm install
  b. Make sure you chnge the .env file wit the mongo db atlas url to your db
  c. npm run server
## About the Restful API
# The routes are authrorized using JWT.

## FOllowing are the routes 
# api/users/ :- To Register the user
# api/users/login :- login to the application
# api/me :- To authorize
# All the API's are authorized using JWT token
# api/goals :- Retrives the golas of a particular user
# api/goals/:id :- to update and delete the goals


## Deployment
# This api is deployed in AWS EC2 instance 
# The Restful API instance is running at this IP http://44.201.27.178:8000
# The client for this api is at https://github.com/lingaiahdanda/GoalSetter-Client
# My free tier AWS S3 has already surprassed 2000 free requests. So i turned off  the client side bucket hosting
# I have deployed my client app in AWS S3 using AWS Code pipeline for CI/CD integration

