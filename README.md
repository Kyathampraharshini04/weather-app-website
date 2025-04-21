# weather-app-website
A responsive web application that displays current weather information and forecasts based on user search or their current location. Built using React and styled with CSS.

## Key Features

* Displays current weather details (temperature, feels like, humidity, wind, conditions) for a searched city.
* Shows weather condition icons.
* Allows users to search for weather by city name.
* (Optional) Fetches and displays weather based on the user's current location (with permission).
* (Optional) Displays a short-term weather forecast.
* Responsive design.

## Technologies Used

* HTML
* CSS
* JavaScript
* React
* [Name of Weather API you used, e.g., OpenWeatherMap API]

## API Key Setup

This application requires an API key from [Name of Weather API you used].

1.  Sign up for a free API key at [Link to the API provider's website].
2.  Create a `.env` file in the root of the project.
3.  Add your API key to the `.env` file like this (replace `YOUR_API_KEY` with your actual key):

    ```
    REACT_APP_WEATHER_API_KEY=YOUR_API_KEY
    ```

4.  Make sure `.env` is included in your `.gitignore` file to prevent your API key from being committed to the repository.

## Installation

1.  Clone the repository: `git clone https://github.com/yourusername/weather-app-internship.git`
2.  Navigate to the project directory: `cd weather-app-internship`
3.  Install dependencies: `npm install` or `yarn install`
4.  Start the development server: `npm start` or `yarn start`
5.  Open your browser and navigate to `http://localhost:3000` (or the address provided by your development server).

## Project Structure

├── public/
├── src/
│   ├── components/
│   │   ├── WeatherDisplay.js
│   │   ├── SearchBar.js
│   │   ├── ForecastDisplay.js (if implemented)
│   │   └── ...
│   ├── App.js
│   └── index.js
├── .env        <-- Add your API key here (and ensure it's ignored by Git)
├── README.md
├── package.json
└── ...

## Challenges Faced and Solutions

* (Mention any challenges and how you overcame them, e.g., handling API rate limits, parsing complex JSON data.)

## Potential Future Enhancements

* Hourly weather forecast.
* Displaying weather maps.
* Saving favorite locations.
* User interface improvements.
* Unit conversion (Celsius/Fahrenheit).

## License

[MIT License](LICENSE)

## Author

[Kyatham praharshini] ([https://github.com/Kyathampraharshini04])
