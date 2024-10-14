#Weather App

This is a weather application that allows users to search for the current weather in any city. It fetches weather data using the OpenWeatherMap API and displays details such as temperature, weather description, feels-like temperature, humidity, and wind speed.

#Features
-----------------------
*Fetches and displays current weather information for any location.
*Shows temperature, weather condition, feels-like temperature, humidity, and wind speed.
*Responsive and clean UI.
*Background image adapts to the app, providing a dynamic and visually appealing experience.

#Technologies Used
------------------------
*Frontend: React.js
*Backend: Node.js (axios for API calls)
*Styling: CSS (including Google Fonts)
*Weather API: OpenWeatherMap API
*Testing: Jest and React Testing Library

#Prerequisites
-------------
Node.js (>= v14.x)
npm (comes with Node.js)

# Installed Applications and Dependencies
------------------------
*axios: For making HTTP requests to the weather API.
*@testing-library/react: For testing React components.
*jest: For running tests.

npm install

#Backend Setup:
------------------
https://api.openweathermap.org/data/2.5/weather?q={city_name}&units=imperial&appid={your_api_key}

#Frontend Setup:
---------------------
The frontend is built using React.js. It allows users to search for the weather in any location by typing in a city name.

#Commands Installed
-------------------------
npm install axios

npm install @testing-library/react

npm install jest

#Backend Setup (Axios for API calls):
------------------
npm install axios

#Frontend Setup (React):
----------------
npx create-react-app weather-app

cd weather-app

npm install axios
npm install @testing-library/react

#How to Run the Application:
------------------
Running the Application in Development Mode:

npm start

Running Tests:

npm test

