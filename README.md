# Weather App

## Description
The Weather App is a simple React application that allows users to search for weather information based on city names. It fetches data from the OpenWeatherMap API and displays the current weather conditions, including temperature, humidity, and wind speed.

## Features
- Search for weather by city name.
- Displays current weather data including temperature, humidity, and wind speed.
- Shows loading state while fetching data.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/weather-app.git
   cd weather-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and add your OpenWeatherMap API key:
   ```plaintext
   REACT_APP_WEATHER_API_KEY=your_api_key_here
   ```

4. Start the application:
   ```bash
   npm start
   ```

## Usage
- Open the application in your browser.
- Enter a city name in the search bar and click the search button to fetch the weather data.
- The application will display the current weather conditions for the specified city.

## API
This application uses the OpenWeatherMap API to fetch weather data. You can sign up for a free API key at [OpenWeatherMap](https://openweathermap.org/api).

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- [React](https://reactjs.org/) - JavaScript library for building user interfaces.
- [OpenWeatherMap](https://openweathermap.org/) - Weather data provider.

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\


### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!


### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

