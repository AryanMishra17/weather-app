# Weather App

This is a simple weather app that fetches and displays weather information for a specified city using the OpenWeatherMap API.

## Features

- Fetches and displays weather information including temperature, weather description, wind speed, and weather icon.
- Allows users to search for weather information by entering a city name.
- Displays the current date and time.
- Responsive design with a modern UI.

## Technologies Used

- HTML
- CSS
- JavaScript
- jQuery
- Moment.js
- OpenWeatherMap API

## Setup Instructions

1. Clone the repository to your local machine.
    ```sh
    git clone <repository-url>
    ```
2. Navigate to the project directory.
    ```sh
    cd weather
    ```
3. Open the `index.html` file in your preferred web browser.

## Usage

1. On page load, the app fetches and displays weather information for the default city (Pune).
2. Enter a city name in the input field and click the "Get Weather" button to fetch and display weather information for the specified city.

## OpenWeatherMap API Setup

The app uses the OpenWeatherMap API to fetch weather information. You need to provide your own API key in the `index.html` file.

1. Sign up at [OpenWeatherMap](https://openweathermap.org/) to get your API key.
2. Replace the `apiKey` variable in the `index.html` file with your API key.
    ```javascript
    const apiKey = 'your_api_key_here'; // Replace with your OpenWeatherMap API key
    ```
