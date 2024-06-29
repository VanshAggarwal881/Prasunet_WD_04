# Prasunet_WD_04
# Weather Web Application
The JavaScript file handles the functionality of fetching and displaying weather data. Here's the key logic:

# Element Selection: 
Selects necessary DOM elements like input box, weather image, temperature, description, humidity, search button, and wind speed.
# checkweather Function: 
Asynchronous function that fetches weather data based on the entered city:
# API Call: 
Uses the OpenWeatherMap API to get weather data.
# Error Handling: 
Displays an error message if the location is not found.
# Update UI: 
Updates the UI with fetched weather data, including temperature, description, humidity, and wind speed.
# Image Update: 
Changes the weather image based on the weather conditions.
# Event Listener: 
Adds a click event listener to the search button to trigger the weather check.
# Functionality
# User Input: 
The user enters a location in the input box.
# Search Button: 
On clicking the search button, the checkweather function is called.
# API Fetch: 
The app fetches weather data from the OpenWeatherMap API.
# Display Data: 
The app updates the weather image, temperature, description, humidity, and wind speed based on the fetched data.
# Error Handling: 
If the location is not found, an error message is displayed.
