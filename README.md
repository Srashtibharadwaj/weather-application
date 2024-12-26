# 🌤️ Weather App

A simple **React** app to check the weather by city using the [OpenWeatherMap API](https://openweathermap.org/api). View key weather details like temperature, humidity, and wind speed!

## 🚀 Features

- Search weather by city name 🌍
- Display temperature 🌡️, humidity 💧, wind speed 🌬️, and weather description ☀️
- Error handling for invalid city names ⚠️
- Loading state while fetching data ⏳
- Responsive design for all devices 📱💻

## ⚙️ Technologies

- **React** for building the UI
- **OpenWeatherMap API** for weather data
- **Axios** for HTTP requests
- **CSS** for styling

## 🐅️ Setup & Installation

1. **Clone the repo**:

   ```bash
   git clone https://github.com/your-username/weather-app.git
   cd weather-app
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Add your OpenWeatherMap API key**:
   - Create a `.env` file in the root directory.
   - Add the following line to the file:
     ```env
     REACT_APP_WEATHER_API_KEY=your_api_key_here
     ```

4. **Start the development server**:

   ```bash
   npm start
   ```

   The app will open at `http://localhost:3000`.

## 📅 File Structure

```
weather-app/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── WeatherCard.js
│   │   ├── SearchBar.js
│   ├── App.js
│   ├── App.css
├── .env                     # API key
└── README.md                # This file
```

## 🌐 API Integration

- Fetch weather data using the `OpenWeatherMap API`.
- Example API endpoint:
  ```bash
  https://api.openweathermap.org/data/2.5/weather?q={city_name}&appid={API_key}&units=metric
  ```

## ✨ Usage

1. Enter a city name in the search bar.
2. Click the search button or press enter.
3. View the current weather details displayed below.

## 🎉 Contributing

Contributions are welcome! Follow these steps:

1. Fork the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature/your-feature-name
   ```

3. Commit your changes:

   ```bash
   git commit -m "Add your message here"
   ```

4. Push to your branch:

   ```bash
   git push origin feature/your-feature-name
   ```

5. Open a pull request.

## ✅ License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
