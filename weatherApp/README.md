# Live Weather App 🌤️

A simple, responsive weather application that shows real-time weather data using the OpenWeatherMap API. Users can search for any city and get current weather conditions including temperature, humidity, and wind speed.

## Features 🌟

- Real-time weather data
- Search by city name
- Displays temperature in Celsius
- Shows humidity percentage
- Displays wind speed
- Dynamic weather icons based on conditions
- Responsive design for all devices
- Clean and modern UI


## Technologies Used 💻

- HTML5
- CSS3
- JavaScript (Vanilla)
- OpenWeatherMap API

## Project Structure 📁

```
weatherApp/
│
├── weather.html
├── styles.css
├── README.md
└── images/
    ├── clear.png
    ├── clouds.png
    ├── drizzle.png
    ├── humidity.png
    ├── mist.png
    ├── rain.png
    ├── search.png
    ├── snow.png
    └── wind.png
```

## Setup Instructions 🚀

Get your API key:
   - Sign up at [OpenWeatherMap](https://openweathermap.org/)
   - Navigate to API keys section
   - Copy your API key

3. Replace the API key
const apiKey = "YOUR_API_KEY_HERE";

4. Open `weather.html` in your browser

## How to Use 📱

1. Enter a city name in the search box
2. Click the search button or press Enter
3. View the current weather details:
   - Temperature
   - Humidity
   - Wind Speed
   - Weather condition icon

## API Response Example 📊

```json
{
  "name": "London",
  "main": {
    "temp": 20,
    "humidity": 65
  },
  "wind": {
    "speed": 5.14
  },
  "weather": [{
    "main": "Rain",
    "description": "moderate rain"
  }]
}
```

## Common Issues & Solutions 🔧

- **City Not Found Error**: Make sure the city name is spelled correctly
- **API Key Issues**: Verify your API key is correctly copied from OpenWeatherMap
- **CORS Issues**: Make sure you're using HTTPS when deploying
- **Images Not Loading**: Check if all image paths are correct

## Future Enhancements 🚀

- Add 5-day forecast
- Add temperature unit conversion (Celsius/Fahrenheit)
- Add geolocation support
- Add loading animations
- Add weather alerts
- Add dark/light mode toggle

## Acknowledgments 👏

- Weather data provided by [OpenWeatherMap](https://openweathermap.org/)
