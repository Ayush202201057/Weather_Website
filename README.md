# Weather_Website
This is a simple weather web application that fetches real-time weather data using the **OpenWeatherMap API**. The application is built using **HTML**, **CSS**, and **JavaScript**, showcasing my understanding of web development fundamentals and how to interact with external APIs.

## 🚀 Features

- Search for weather in any city by name
- Displays:
  - Temperature
  - City name
  - Weather icon (changes dynamically)
  - Humidity level
  - Wind speed
- Handles invalid city input with user-friendly error messages
- Responsive and clean UI

- ## 📦 How It Works

1. User enters a city name and clicks the **Search** button.
2. JavaScript uses the `fetch()` function to make a GET request to the OpenWeather API.
3. The response is parsed using `JSON`.
4. If the city is valid:
   - The temperature, humidity, wind speed, and weather icon are displayed.
5. If the city is invalid:
   - An error message is shown instead of weather details.
  
   
