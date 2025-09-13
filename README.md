# Weather-App

A simple and responsive Weather App built using HTML, CSS, and JavaScript that allows users to check the current weather conditions of any city in the world. The app fetches real-time weather data using the OpenWeatherMap API.
A Weather App

A simple weather application built with HTML, CSS, and JavaScript that displays current weather information for any city using the OpenWeatherMap API.

## Features

-   Search for weather by city name
-   Displays temperature, humidity, wind speed, and weather icon
-   Shows error message for invalid city names
-   Responsive and modern UI

## Demo

![Weather App Screenshot](images/clouds.png)

## Getting Started

### Prerequisites

-   Modern web browser
-   Internet connection

### Setup

1. Clone or download this repository.
2. Open `index2.html` in your browser.
3. Enter a city name and click the search button to view the weather.

### API Key

This app uses the OpenWeatherMap API. The API key is currently hardcoded in `script.js` for demonstration purposes. For production, use a backend to keep your API key secure.

You can get your own API key from [OpenWeatherMap](https://openweathermap.org/api).

Replace the value of `apiKey` in `script.js` with your own key:

```js
const apiKey = "YOUR_API_KEY_HERE";
```

## Project Structure

```
index2.html
script.js
style.css
images/
	clear.png
	clouds.png
	drizzle.png
	humidity.png
	mist.png
	rain.png
	search.png
	snow.png
	wind.png
```

## Deployment

You can deploy this app on any static hosting service (GitHub Pages, Vercel, Netlify, etc.).

## License

This project is for educational purposes.
