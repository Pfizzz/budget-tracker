# Pfizz's Budget Tracker

## A Progressive Web Application 

![image](https://github.com/Pfizzz/budget-tracker/blob/ec031b9dda5fa1f1f41c3c7ffab38160d4b1cf8a/images/ss1.png)
Image demonstrates the application uploading data when set back into an "online" state.

LIVE LINK : [Heroku](https://budget-tracker-0512.herokuapp.com/)

## Project Information

This project's task was to add offline functionality to a javascript-based budget tracking application. 
* manifest.json was created with appropriate metadata.
* idb.js holds all functionality related to IndexedDB and stores data when the application is in an offline state
* service_worker.js was created to cache all the files to upload data when the app goes online.

## Installation

* This app may be viewed in its deployed Heroku link above.
* To operate on a local server, clone the repo, navigate to the root directory, and execute 'npm i' to install dependencies.
* Run 'node server' to start the app.
* Navigate to localhost:3000 in your browser to view the app.
* On Chrome, open DevTools to throttle the newtwork, enter data, connect to the network again and update the database.
