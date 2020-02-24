Code for MERN tutorial.
==========================
SIMPLE EXERCISE TRACKER USING MONGODB-EXPRESS-REACT-NODE
=========================================================

Using Mongo DB Atlas Account.

Add your connection URI at backend/.env file

Installation Instructions
==================

git clone https://github.com/saurav90/mern-stack.git

Installing node-modules for frontend
======================================

$ cd mern-stack</br>
$ npm install

Installing node-modules for backendInstallation
======================================

$ cd backend</br>
$ npm install

Setting Up MongoDB Atlas Connection
======================================

Go to backend directory and paste your atlas connection URI there.</br>
ATLAS_URI = --Add Your Atlas Connection URL here -- (without quotes)</br>
If you are using mongoDB in your local machine then use mongodb://localhost:27017/test.</br>
For example: ATLAS_URI = mongodb://localhost:27017/test

Running the Application
=========================
$ npm run dev </br>

This will start the backend express server and frontend react-scripts concurrently. You can also use two different terminals to start the frontend and backend separately</br>

type npm start on mern-stack directory in one terminal  and </br>
type nodemon server on backend directory in another terminal
