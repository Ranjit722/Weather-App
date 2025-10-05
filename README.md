# Weather App

A modern, responsive web application that provides real-time weather information, forecasts, and air quality data for any city or your current location.

## Features

- **Current Weather**: Displays current temperature, weather conditions, and location details.
- **5-Day Forecast**: Shows daily weather forecasts with icons and temperatures.
- **Hourly Forecast**: Provides hourly weather updates for the next 24 hours.
- **Air Quality Index**: Displays comprehensive air quality data including PM2.5, PM10, SO2, CO, NO, NO2, NH3, and O3 levels.
- **Weather Highlights**: Includes sunrise/sunset times, humidity, pressure, visibility, wind speed, and "feels like" temperature.
- **Location Services**: Supports searching by city name or using geolocation for current location.
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices.
- **Loading Spinner**: Visual feedback during data fetching.
- **Error Handling**: User-friendly alerts for failed API requests or invalid inputs.

## Technologies Used

- **HTML5**: Structure and semantic markup
- **CSS3**: Styling with responsive design, animations, and modern layout techniques
- **JavaScript (ES6+)**: Core functionality and API interactions
- **OpenWeatherMap API**: Weather data, forecasts, and air quality information
- **FontAwesome**: Icons for UI elements
- **Moment.js**: Date and time formatting
- **Boxicons**: Additional icon library

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weather-app.git
   cd weather-app
   ```

2. Open `index.html` in your web browser.

No additional installation or build process is required. The app runs entirely in the browser.

## Usage

1. **Search by City**: Enter a city name in the input field and click the search button or press Enter.
2. **Current Location**: Click the "Current Location" button to get weather data for your current position (requires location permission).
3. **View Data**: Explore current weather, forecasts, air quality, and other highlights in the responsive interface.

## API Configuration

This app uses the OpenWeatherMap API. To use your own API key:

1. Sign up for a free account at [OpenWeatherMap](https://openweathermap.org/api)
2. Get your API key from the dashboard
3. Replace the `api_key` variable in `script.js` with your key:
   ```javascript
   let api_key = 'your-api-key-here';
   ```

## Screenshots

![Weather App Screenshot](https://via.placeholder.com/800x400?text=Weather+App+Screenshot)

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

[Ranjit.T](https://github.com/Ranjit722)

## Acknowledgments

- Weather data provided by [OpenWeatherMap](https://openweathermap.org/)
- Background image from [Unsplash](https://unsplash.com/)
- Icons from [FontAwesome](https://fontawesome.com/) and [Boxicons](https://boxicons.com/)
