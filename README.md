**Weather App**
A simple weather application that allows users to fetch and display current weather and a 24-hour forecast for any city using the OpenWeatherMap API.

**Features**
- Displays the current temperature, weather condition, and an appropriate weather icon.
- Shows a 24-hour forecast with temperature, weather icons, and time (in 3-hour intervals).
- Provides dynamic content updates based on user input.

**Technologies Used**

- HTML5: Structure of the application.
- CSS3: Styling and layout.
- JavaScript: Logic for fetching weather data and updating the UI.
- OpenWeatherMap API: Source of weather data.

**How to Run the Project**

Prerequisites
Before you begin, ensure you have the following installed:

A modern web browser
Internet connection (required to fetch weather data)
Getting Started
Clone the repository:

**bash**

Copy code

git clone https://github.com/your-username/weather-app.git

Open the project directory:

**bash**

Copy code

cd weather-app

- Open index.html in your browser to start the app.

- OpenWeatherMap API Key
This project uses the OpenWeatherMap API to fetch weather data. You need an API key to make requests.

- Sign up at OpenWeatherMap to get your free API key.

- Replace the placeholder API key in the getWeather() function in script.js:

**javascript**
Copy code
const apiKey = 'your-api-key-here';

**How It Works**
- The user inputs the city name.
- The app fetches the current weather and 24-hour forecast using the OpenWeatherMap API.
- The app dynamically updates the UI to display the fetched weather data, including temperature, description, and weather icons.

**Possible Improvements**

- Add more detailed weather information (e.g., wind speed, humidity).
- Implement unit switching (Celsius/Fahrenheit).
- Enhance UI/UX with better styling and responsiveness.
- Display weather for multiple cities or allow saving favorite locations.
