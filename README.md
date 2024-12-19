# geekirui120-phase-1-final-projectphase-1-final-project
Weather Update Application

Overview

The Weather Update Application is a dynamic web application that allows users to search for current and future weather conditions for any city. Built with HTML, CSS, JavaScript, and the OpenWeatherMap API, this app provides a seamless and interactive experience to check weather updates and maintain a search history.

Features

Search for Weather: Users can search for a city's current weather conditions, including temperature, humidity, wind speed, and UV index.

5-Day Weather Forecast: Displays a 5-day weather forecast with key details such as date, temperature, humidity, and weather icons.

Search History: Keeps a history of previously searched cities for quick access.

Clear History: Option to clear the search history.

Responsive Design: Works well across various screen sizes and devices.

Technologies Used

Frontend: HTML5, CSS3, Bootstrap 4, Font Awesome

JavaScript: jQuery for DOM manipulation and AJAX requests

API: OpenWeatherMap API

Getting Started

Prerequisites

A modern web browser (e.g., Chrome, Firefox, Safari, or Edge).

Internet connection for accessing the OpenWeatherMap API and external libraries.

Installation

Clone the Repository:

git clone https://github.com/your-username/weather-update.git

Navigate to the Project Directory:

cd weather-update

Open the Application in a Browser:
Open the index.html file in any modern browser.

Usage

Search for a City: Enter the city name in the search bar and click the search button (magnifying glass icon).

View Weather Details: The application displays the current weather and a 5-day forecast for the searched city.

Access Search History: Click on a city in the search history to view its weather details again.

Clear Search History: Use the "Clear History" button to remove all previously searched cities.

Application Structure

HTML (index.html): Defines the structure and layout of the application.

CSS (style.css): Handles the styling of the application, ensuring it is visually appealing and responsive.

JavaScript (script.js): Contains the logic for handling user interactions, fetching data from the OpenWeatherMap API, and updating the DOM dynamically.

API Integration

The application uses the OpenWeatherMap API for fetching weather data. Replace the placeholder API key in script.js with your personal API key:

var APIKey = "your-api-key-here";

API Endpoints Used

Current Weather Data:

https://api.openweathermap.org/data/2.5/weather?q={city_name}&APPID={APIKey}

5-Day Weather Forecast:

https://api.openweathermap.org/data/2.5/forecast?id={city_id}&appid={APIKey}

UV Index:

https://api.openweathermap.org/data/2.5/uvi?appid={APIKey}&lat={lat}&lon={lon}

Project Files

index.html: Main HTML file for the application.

style.css: Custom CSS styles for the application.

script.js: JavaScript file containing the logic for API calls, DOM manipulation, and event handling.

Troubleshooting

Search Button Not Working: Ensure jQuery is loaded correctly and there are no syntax errors in script.js.

API Key Issues: Verify that the API key is valid and has appropriate permissions.

Network Errors: Check your internet connection and ensure the API endpoints are accessible.

Future Enhancements

Add geolocation support to automatically detect the user's location.

Include additional weather details such as sunrise/sunset times and atmospheric pressure.

Implement error handling for invalid city searches.

Use local storage to persist user preferences, such as units of measurement (Celsius/Fahrenheit).

License

This project is open-source and available under the MIT License.

Thank you for using the Weather Update Application! Feel free to contribute or provide feedback to enhance the application.

