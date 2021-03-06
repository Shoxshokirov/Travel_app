# Capstone Project: Travel Journal


## Overview

A Travel Journal app to **log past and future trips**, together with a picture of the destination and weather information.

The searches can added and removed from the log with the **save** and **delete** functionalities.

The trip information relies on data from **multiple APIs** and the requests are served by **Express.js** web server. A development and a production mode has been configured with **Webpack** with service workers in production.

## Objective

This project was aimed at practicing:

- DOM manipulation
- Dev and Prod modes
- Webpack Loaders and Plugins
- Sass
- Flexbox
- Service workers
- Express
- External APIs
- Basic Jest testing

## Get Started

In order to run this application locally make sure you signup to:

- [Geonames](https://www.geonames.org/)
- [Weatherbit](https://www.weatherbit.io/api)
- [Pixabay](https://pixabay.com/api/docs/)

You will need to create a new `.env` file in the root of your project and store your API keys like so:

```
WEATHERBIT_KEY = ********************
PIXABAY_KEY = ***********************
GEONAMES_USER = *********************
```

## From Terminal

`npm install` - to install required packages

`npm run test` - to run tests

`npm run build-dev` - to build the app in development mode and start the webpack server

`npm run build-prod` - to build in production mode

`npm run start` - to start the server with the built production app

## Acknowledgments

This app is the final project for [Udacity](https://www.udacity.com/) **Front End Web Developer Capstone Project**

