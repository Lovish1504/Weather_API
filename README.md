# Python Weather API Project

This Python project utilizes the OpenWeatherMap API to retrieve weather data for a specified city and display it in the console.

## Overview

The project aims to provide users with real-time weather information for a given city using the OpenWeatherMap API. The script prompts users to input a city name and fetches weather details like description, temperature, humidity, and wind speed.

## Prerequisites

- Python 3.x installed
- `requests` library (`pip install requests`)
- OpenWeatherMap API Key (Obtain one by signing up at [OpenWeatherMap](https://openweathermap.org/api))

## How to Use

1. **Obtain API Key**

   Sign up for an account at [OpenWeatherMap](https://openweathermap.org/api) to obtain an API key.

2. **Python Code**

   ```python
   # Insert the provided Python code here, replacing 'YOUR_API_KEY_HERE' with your API key.
   ```

3. **Usage**

   - Run the Python script.
   - Enter the city name when prompted.
   - The script will make a request to the OpenWeatherMap API and display weather information for the entered city.

## Python Code Explanation

- The Python script uses the `requests` library to make an API call to OpenWeatherMap.
- It constructs the API request with the specified city name and the API key obtained from OpenWeatherMap.
- Upon a successful API response (status code 200), it extracts weather data (description, temperature, humidity, wind speed) and displays it in the console.

## Notes

- Replace `"YOUR_API_KEY_HERE"` in the Python code snippet with the API key you received from OpenWeatherMap.
- Error handling: Ensure to include error handling for cases like failed API requests or invalid city names.

## License

This project is open-source and available under the [MIT License](LICENSE).
