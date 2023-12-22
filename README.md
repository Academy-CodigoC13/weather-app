# weather app

Monolithic app to consume openweathermap API

## Description

This app is a monolithic app that consumes the openweathermap API to get the
weather of a city. It has a simple UI that allows the user to enter a city name
and get the weather of that city. The app is written in JavaScript and uses the
express framework. It also uses the native fetch API to make the API call to
openweathermap.

## Use

To use the app, simply enter a city name in the input field and click the submit
button. The app will then make a call to the openweathermap API and return the
weather of that city. The weather will be displayed in the UI.

## Architecture

### View

The view is a simple HTML page with a form that allows the user to enter a city
name and a submit button. The form is submitted to the server when the submit
button is clicked. and use the enpoint `/weather/:city` to make the API call to
openweathermap.

### API

The API is a simple express server that serves the data from the API
openweathermap. The API call is made when the form is submitted.

## Installation

To install the app:

- Clone the repo and run `npm install` to install the dependencies.
- Then run `npm start` to start the API. The API will be running on port 3000.
- Open a browser and navigate to the html or use live server from VSCode IDE instead
