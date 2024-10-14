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


#Home Page (User List)

*Displays a table with the list of users (name, email, ID).
*Users can delete or edit entries.
*A button is provided to navigate to the "Create User" page.
![Screenshot 2024-10-14 190332](https://github.com/user-attachments/assets/eaca3236-fca0-4f58-961c-a9e198571025)

#Create User Page

*Allows users to fill in a form to add new users with a name and email.
*Once submitted, the new user is added to the user list and displayed on the Home page.
![Screenshot 2024-10-14 190432](https://github.com/user-attachments/assets/387891f8-0cc8-4a54-b795-d105b3634cd3)

#Update User Page

*Users can update the name and email of an existing user.
*Once updated, the information is reflected on the Home page.
![Screenshot 2024-10-14 190451](https://github.com/user-attachments/assets/e24df225-a61b-4e3b-8eb8-d81b1dcac38c)


![Screenshot 2024-10-14 190505](https://github.com/user-attachments/assets/a79bd963-6e06-49b1-9df2-436c0076972d)
#Delete

![Screenshot 2024-10-14 190533](https://github.com/user-attachments/assets/a707761f-45c4-4d49-bc5d-edfeade4102c)
![Screenshot 2024-10-14 190649](https://github.com/user-attachments/assets/3e50bf65-8a9f-4dea-934d-82f356e4eeb1)


