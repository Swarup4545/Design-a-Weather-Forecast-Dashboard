# Submission Guidelines

## Weather App

This project consists of a weather application built with React. It displays the current weather and a 5-day forecast for a specified city using data from the OpenWeatherMap API.

### Prerequisites

Before running the project locally, make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Swarup4545/Design-a-Weather-Forecast-Dashboard.git  (<repository-url>)
   
2.Change to the project directory:  
  cd myapp (cd <project-directory>)
  
3.Install dependencies:
  npm install
  npm init (for package.json)
  
4.Configuration:-
                1.Get an API key from OpenWeatherMap by signing up for a free account.
                2.Create a .env file in the root directory and add your API key:
                  REACT_APP_WEATHER_API_KEY=your-api-key
                  
5.To run the app locally, use the following commands:
  npm start
  This will start the development server. Open your browser and navigate to 
  http://localhost:3000 to view the app.  (localhost:3000 port is by default port for reactjs and for angular default port 4200)

*Usage:-
       -Enter a city name in the search input to get the current weather and forecast.
       -Toggle between Celsius and Fahrenheit using the provided buttons.
       -Scroll down to view the 5-day weather forecast with a typewriter effect.
*Notes:-
       -The project uses React, including hooks and functional components.
       -Weather data is fetched from the OpenWeatherMap API.
       -Images are dynamically loaded based on the weather conditions.  
       
Feel free to explore and customize the project as needed. Happy coding!  


Replace `<repository-url>` and `<project-directory>` with the appropriate values for your project. Additionally, provide your OpenWeatherMap API key in the `.env` file.

This README.md file provides users with clear instructions on how to set up and run the project locally.

