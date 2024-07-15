Weather App - HTML, CSS, JavaScript
This project implements a simple weather application using HTML, CSS, and JavaScript. The app allows users to check the current weather of any city by fetching data from a weather API.

Table of Contents
Introduction
Features
Installation
Usage
API Integration
Project Structure
Introduction
The Weather App is a basic web-based application designed to provide real-time weather information for any city. The app uses a clean and intuitive interface, making it easy for users to search for and view current weather conditions.

Features
Search for weather by city name
Display current temperature, weather conditions, and other relevant data
Responsive design for optimal viewing on different devices
Installation
Clone the repository:
git clone https://github.com/Chukwuskindall/weather-app.git
cd Weather-App-Html-Css-Js
Open the application:
Simply open the index.html file in your preferred web browser.

Usage
Enter City Name:

In the search box, type the name of the city for which you want to check the weather.
Submit Search:

Click the "Search" button or press Enter to fetch and display the weather data for the specified city.
View Weather Data:

The app will display the current temperature, weather conditions, humidity, wind speed, and an icon representing the weather.
API Integration
The application integrates with the OpenWeatherMap API to fetch weather data. Ensure you have a valid API key and update the script.js file with your key.

Sign up for an API key:

Go to OpenWeatherMap and sign up for a free API key.
Add your API key to script.js:

Open the script.js file and replace YOUR_API_KEY with your actual API key.
const apiKey = 'YOUR_API_KEY';
Project Structure
Weather-App-Html-Css-Js/
│
├── index.html               # Main HTML file
├── style.css                # CSS file for styling
└── script.js                # JavaScript file for functionality
