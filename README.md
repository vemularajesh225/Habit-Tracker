# Habit Tracker

# Project Overview

This is a simple habit tracker web app,  where we can define habits and track them.
## Features 

* Add multiple habits to track like reading a book, going to the gym etc
* Track each habit everyday. These are the 3 statuses of a habit:
    * Done - Mark the habit as done for a day
    * Not done - Mark the habit as not done for a day
    * None - User did not take any action on a habit for a day
* A view to show all current habits.

# Tech Stack
HTML

CSS

JAVASCRIPT

# Getting Started with Create React App

Hosted link :(https://vemularajesh225.github.io/Habit-Tracker/)

First of all create react project using create-react-app app_name

Delete the unnecessary files

**Folder structure**

habit-tracker/
│
├── public/
│   ├── index.html
│   └── favicon.ico
│
├── src/
│   ├── assets/
│   │   └── background.jpg
│   │
│   ├── components/
│   │   ├── AddHabit/
│   │   │   └── AddHabit.js
│   │   ├── List/
│   │   │   └── List.js
│   │   ├── Navbar/
│   │   │   └── Navbar.js
│   │   ├── Weekview/
│   │   │   └── Weekview.js
│   │   └── Home/
│   │       └── Home.js
│   │
│   ├── redux/
│   │   ├── actions/
│   │   │   └── habitActions.js
│   │   ├── reducers/
│   │   │   └── habitReducer.js
│   │   └── Store.js
│   │
│   ├── App.js
│   ├── index.js
│   └── index.css
│
├── node_modules/
├── .gitignore
├── package.json
├── README.md
└── other_config_files...


## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

