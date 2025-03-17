# Weather App

A simple, elegant weather application that provides current weather conditions for any city.

## Features

- Search for weather by city name
- Display current temperature in Celsius
- Show weather conditions (sunny, cloudy, etc.)
- Day/night visualization based on current time at location
- Clean, responsive UI using Materialize CSS framework

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Materialize CSS
- AccuWeather API for weather data
- Font Awesome icons
- Google Fonts

## How to Use

1. Clone this repository to your local machine
2. Open `index.html` in your web browser
3. Enter a city name in the search box
4. Press Enter or click the search icon to view weather information

## API Configuration

This application uses the AccuWeather API to fetch weather data. The API key is included in the code for demonstration purposes. In a production environment, it's recommended to:

1. Create your own API key at [AccuWeather Developer Portal](https://developer.accuweather.com/)
2. Replace the existing key in `index.js` with your own key
3. Consider using environment variables or a backend service to secure your API key

## Project Structure

```
├── assets/
│   ├── Day.png
│   └── Night.png
├── index.html      # Main HTML file
├── style.css       # CSS styles
├── index.js        # API connection code
├── app.js          # Application logic
└── README.md       # Project documentation
```

## Future Enhancements

- Add forecast for upcoming days
- Add geolocation to automatically detect user's city
- Add option to switch between Celsius and Fahrenheit
- Implement local storage to save user's last searched city
- Add more weather details (humidity, wind speed, etc.)

## Author

Created by Swayam Dani

## License

This project is open source and available under the [MIT License](LICENSE).
