# Zarektronix Assignment
## SignUp in hybrid mode

## Introduction
A mern stack application for managing or registering users online and offline.

## Features
The key features of the application.

- User can sign in online mode
- User can sign in to offline mode

## Deployed link
[link](https://zatroni-frontend.vercel.app/)

## Demo Vedio link
[link](https://drive.google.com/file/d/14cH6rSTei-nU3DVKhboDQIOIM78s4CL-/view?usp=sharing)

## Installation or How to run the app
I created cloud database using MongoDb Atlas. So, if you want to run our code then please read the instructions below :
- Clone our repository `https://github.com/harishreyya/zarektronix.git`
- Open the code in your VS code, open Backend folder in the terminal by running `cd Backend`
-Now run `npm install` or `npm i` which will install all the required packages of node
- After installation, now run `npm run server` and  you will see `server is listening on 5123` 
- Simultaneously, open a new terminal and run `cd frontend` by which you get into frontend folder
- Now here, run `npm install` or `npm i` which will install all the required packages of react as well
- After installation, now run `npm start` and  you will see a new window will be opening in the default browser which is running on port `http://localhost:3000`
- Now you see app running, you can click on `Register` to sign up both in online and offline mode.



## API Endpoints
Backend Applications provide a list of API endpoints
- POST /registerOnline - register a new user online mode
- POST /registerOffline - register a new user offline mode

## Technology Stack
List and provide a brief overview of the technologies used in the project.

- MongoDB
- Express JS
- React JS
- Node JS
 
 ### Dependencies and packages

#### Backend
- `mongoose`<br/>
  connecting MongoDB to the Node js server
- `nodemon`<br/>
  It monitors your project and automatically restarts when it detects any changes.
- `cors`<br/>
  allowing browser should permit the loading of resources

#### Frontend
- `axios`<br/>
  JavaScript library to make HTTP requests or fetch data
- `react-router-dom`<br/>
  implementation of dynamic routing 

#### Cloud Deployment

- `Render`
used Render for deploying the MongoDB (database), node js (Backend) 
- `Vercel`
used Vercel for deploying React JS (frontend)
