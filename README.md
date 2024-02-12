# js-weather-app
<img src="weather app.gif">


# Weather App Documentation
This document details about the code structure, functionality,
and API used in the weather app.

## 1. Overview
The weather app retrieves weather information for a user-specified
location or the user's current location. It utilizes the
OpenWeatherMap API to fetch data and displays it in a
user-friendly interface.

## 2. Technologies Used
-   HTML5
-   CSS3
-   JavaScript
-   OpenWeatherMap API

## 3. Code Structure
### index.html:
Defines the basic structure of the app, including HTML elements and
references to the CSS and JavaScript files.
### app.css:
-   Styles the app's interface elements.
### app.js:
-   Contains the core JavaScript logic for:
-   User input handling (city name or location detection)
-   API calls to OpenWeatherMap
-   Parsing and displaying the retrieved weather data
-   Error handling and UI updates

## 4. Functionality
### Location Input:
-   Users can enter a city name or use their current location through
the browser's geolocation API.
-   Input validation ensures valid city names or geolocation
availability.
### API Calls:
-   The app constructs API requests based on the chosen location.
-   The OpenWeatherMap API key is securely stored and used for
authentication.
-   Error handling covers network issues or invalid API responses.
### Weather Data Display:
-   Fetched data is parsed and relevant information like temperature,
weather description, humidity, and feels-like temperature are
extracted.
-   Custom weather icons are shown based on the retrieved weather ID.
-   Units (Celsius/Fahrenheit) can be customized (implementation
optional).
### Additional Features:
-   Implement features like five-day forecast, wind speed,
sunrise/sunset times, etc. (optional).

## 5. Development Notes
-   Considering responsive design for various screen sizes.
-   Robust error handling for different scenarios (not all errors
catered for).
-   Unit tests for core functionalities.

## 6. Further Resources
-   OpenWeatherMap API Documentation: https://openweathermap.org/api
-   HTML/CSS/JavaScript documentation (as needed)

## 7. Screenshots of Live App
<img align="left" alt="C" style="padding-right;" src="screenshots/weather-app-home.PNG">
<img align="left" alt="C" style="padding-right;" src="screenshots/weather-app-location-1.PNG">
<img align="left" alt="C" style="padding-right;" src="screenshots/weather-app-location-2.PNG">
<img align="left" alt="C" style="padding-right;" src="screenshots/weather-app-location-3.PNG">
<img align="left" alt="C" style="padding-right;" src="screenshots/weather-app-world-1.PNG">
<img align="left" alt="C" style="padding-right;" src="screenshots/weather-app-world-2.PNG">
<img align="left" alt="C" style="padding-right;" src="screenshots/weather-app-world-3.PNG">



