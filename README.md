# Automated-WeatherForecast-App


The Weather Forecasting Tool is a command-line application that provides current weather forecasts for cities. It leverages the OpenWeatherMap API to fetch weather data and uses Python for data parsing and text-to-speech functionality. This project showcases how GitHub Copilot, an AI-powered coding assistant, assists in API usage, data parsing, error handling, and code efficiency improvements.

# Features
* Current Weather Forecast: Get real-time weather information for a specified city, including description, temperature in Celsius, and humidity.
* Text-to-Speech: Hear the weather forecast read aloud with the integrated text-to-speech functionality.
* Decision-Making: Determine whether it's suitable to go out based on the weather conditions and receive appropriate suggestions.
* Destination Suggestions: If planning a trip, get weather forecasts for the destination city, along with travel suggestions and activities to do during the trip.
* GitHub Copilot Assistance: Throughout the development process, GitHub Copilot provides valuable suggestions, enhancing API usage, data parsing, error handling, and overall code efficiency.

https://github.com/Fastest-Coder-First/Hackathon-Abhi/assets/136588531/1c9129fd-44b7-4c51-895a-ba891010ef33


# APIs Used
OpenWeatherMap API: Used to fetch weather data for current and destination cities.
# How GitHub Copilot Assisted
GitHub Copilot played a significant role in developing the Weather Forecasting Tool project. It provided suggestions and assistance with API usage, data parsing, error handling, and code optimization. By leveraging GitHub Copilot's AI-powered capabilities, the development process was streamlined, leading to more efficient and reliable code.

GitHub Copilot played a vital role in the following areas:
* API Usage: It provided intelligent suggestions for integrating the OpenWeatherMap API, simplifying HTTP requests, response handling, and data extraction from JSON.
* Data Parsing: GitHub Copilot assisted in efficiently parsing the weather data, offering suggestions for extracting relevant information like temperature, weather description, and humidity from the API response.
* Error Handling: It contributed to robust error handling by suggesting error checks, exception handling, and error message customization, ensuring the code gracefully handles unexpected scenarios.
* User Input Validation: GitHub Copilot provided valuable assistance in validating user inputs, guiding the implementation of input validation for yes/no and time (AM/PM) inputs, improving the program's reliability.
* Code Refactoring and Structure: It suggested code refactoring techniques and structural improvements, leading to better code organization, modularization, and maintainability.

GitHub Copilot proved to be an invaluable tool throughout the development process, significantly reducing development time, enhancing code accuracy, and providing helpful insights and suggestions along the way.


## Usage

1. Run the application:
2. Follow the prompts to enter the current city, indicate if you plan to go out or travel, and provide necessary details.
3. The tool will display the current weather forecast, along with suggestions based on the weather conditions.
4. If applicable, the tool will also provide weather information for the destination city, along with travel suggestions and activities to consider during the trip.


## Dependencies

The Weather Forecasting Tool relies on the following dependencies:
- `requests`: Used for making HTTP requests to the OpenWeatherMap API.
- `json`: Used for parsing the JSON response from the API.
- `gtts`: Used for text-to-speech functionality.
- `tempfile`: Used for creating a temporary file for the audio output.
- `pygame`: Used for playing the generated audio.

Make sure to install these dependencies using the `pip install` command mentioned in the Installation section.


