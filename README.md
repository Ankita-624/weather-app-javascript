# weather-app-javascript
A JavaScript weather app that fetches and displays current weather data for any city using the OpenWeatherMap API.
# JavaScript Weather Application

A simple web application built with HTML, CSS, and JavaScript that retrieves and displays weather information for a specified city using the OpenWeatherMap API.

## Features

*   **City-Specific Weather:** Enter a city name to retrieve its current weather conditions.
*   **Temperature Display:** Shows the current temperature in Celsius.
*   **Weather Description:** Provides a brief description of the weather conditions (e.g., "clear sky," "scattered clouds").
*   **Error Handling:** Displays an error message if the city is not found.

## Technologies Used

*   **HTML:** For structuring the web page.
*   **CSS:** For styling the application and its components.
*   **JavaScript:** To handle user interaction, API requests, and display the weather information.
*   **OpenWeatherMap API:** To fetch real-time weather data.

## Setup and Usage

1.  **Clone the repository:**

    ```
    git clone https://github.com/Ankita-624/weather-app-javascript.git
    ```

2.  **Open `index.html` in your browser:**

    Navigate to the cloned directory and open the `index.html` file in your web browser.

3.  **Enter a city name:** Type the name of the city in the input field.

4.  **Get the weather:** Click the "Get Weather" button to display weather information or press enter.

## API Key

*   This application uses the OpenWeatherMap API to fetch weather data. You will need to replace the API key in `script.js` with your own to start running the app.

## Functionality Details

*   **Input:** The user enters a city name in the input field.
*   **API Request:** The JavaScript code makes a request to the OpenWeatherMap API using the entered city name.
*   **Data Display:** If the city is found, the weather information (city name, temperature, and description) is displayed on the page.
*   **Error Handling:** If the city is not found, an error message is displayed.

## Future Enhancements

*   **More Detailed Weather Information:** Add additional weather details such as humidity, wind speed, and pressure.
*   **Location-Based Weather:** Implement geolocation to automatically detect the user's location and display weather information for their current city.
*   **Weather Icons:** Display weather icons to visually represent the weather conditions.

## Author

Ankita Gouda

## License

This project is licensed under the MIT License - see the LICENSE file for detailed terms.
