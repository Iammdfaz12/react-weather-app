# React.js Weather Application

This React.js Weather Application provides real-time weather updates for any city, along with a 5-day forecast. The application uses a clean, minimalistic design to display weather details clearly and efficiently.

## Features

- **Current Weather**: View the current weather conditions for any city.
- **5-Day Forecast**: Get a detailed weather forecast for the next 5 days.
- **Search Functionality**: Search for weather updates by city using an interactive search box.
- **Minimalistic Design**: User-friendly and visually appealing interface.
- **Accordion for Forecast**: Expand and view detailed weather information for each day using the Accordion library.
- **Async Paginate**: Efficient city search with pagination for smooth performance.

## Technologies Used

- **React.js**: Frontend framework for building the user interface.
- **Rapid API Hub**: For accessing weather data.
- **OpenWeather API**: Primary source of weather information.
- **Accordion Library**: For displaying collapsible forecast details.
- **Async Paginate Library**: For implementing the city search functionality.

## Installation

1. Install dependencies:

   ```bash
   npm install
   ```

2. Add your API keys:

   - Create a `.env` file in the root directory.
   - Add your API keys in the following format:

     ```env
     WEATHER_API_KEY = your-openweather-api-key
     ```

3. Start the development server:

   ```bash
   npm start
   ```

---

## Project Structure

```plaintext
src/
├── components/
│   ├── current weather/
|   |   |___current-weather.css
|   |   |___current-weather.js
|   |
│   ├── forecast
|   |   |___forecsast.css
|   |   |___forecast.js
|   |
│   ├── search
|   |   |___search.js
|   |
├── api.js
├── App.js
├── index.js

```

- current-weather.js: Displays the current weather details.
- forecast.js: Shows the 5-day forecast using the Accordion library.
- search.js: Provides a search box to find weather details of a city.
- api.js: Handles API calls and data formatting.

## How to Use

1. Enter the name of the city in the search box.
2. View the current weather details displayed on the main screen.
3. Expand the forecast section to view the 5-day weather details.

## Libraries Used

- React.js
- Rapid API Hub
- OpenWeather API
- Accordion Library
- Async Paginate Library

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
