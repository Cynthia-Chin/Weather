# Weather App 🌤️
## Overview
This Weather App allows users to view current weather and a 3-day forecast for any city or their current location. The app is built with HTML, CSS, JavaScript, and uses the OpenWeatherMap API for real-time weather data.

## Features
- Search weather by city name
- Fetch weather based on user’s current location
- Toggle temperature units between Celsius and Fahrenheit
- Display current weather information:
  - Temperature
  - Weather description
  - Humidity
  - Wind speed
  - Weather icon
- Show 3-day forecast with icon, and temperature
- Responsive layout for desktop and mobile
- Input validation to prevent empty searches

## Installation
1. Clone the repository: `git clone https://github.com/Cynthia-Chin/Weather.git`
2. Open index.html in your browser.
3. Make sure you have an internet connection to fetch the OpenWeatherMap API.

## Setup
1. Sign up at [OpenWeatherMap](https://openweathermap.org/) and get your API key.
2. In `weather.js`, replace the `API_KEY` constant with your own: `const API_KEY = "YOUR_API_KEY_HERE";`

## Usage
1. Enter a city name and click the Search button.
2. Click the 📍 Use My Location button to fetch weather based on your current location.
3. Switch between Celsius and Fahrenheit using the unit buttons.

## Technologies Used
- HTML5
- CSS3 (Flexbox, responsive design)
- JavaScript (ES6+, Fetch API)
- OpenWeatherMap API


## Notes / Tips
- Geolocation only works on secure origins (HTTPS).
- Empty city input is handled gracefully with a warning message.
- Forecast data is filtered to show 3 days at 12:00 PM

## License
This project is licensed under the MIT License.
