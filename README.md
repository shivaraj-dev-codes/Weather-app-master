# Weather App 🌤️

A simple and clean weather web application built with **HTML, CSS, and JavaScript**. Search any city in the world and instantly get the current weather, temperature, humidity, and wind speed.

---

## Features

- Search weather by city name
- Displays current temperature (°C)
- Shows humidity and wind speed
- Dynamic weather icons (Clouds, Clear, Rain, Drizzle, Mist)
- Error handling for invalid city names
- Powered by the [OpenWeatherMap API](https://openweathermap.org/api)

---

## Demo

> Search for any city → get live weather data instantly.

---

## Tech Stack

| Layer      | Technology              |
|------------|-------------------------|
| Markup     | HTML5                   |
| Styling    | CSS3                    |
| Logic      | JavaScript (Vanilla)    |
| API        | OpenWeatherMap REST API |

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/shivaraj-dev-codes/Weather-app-master.git
cd Weather-app-master
```

### 2. Add your API key

Open `index.html` and replace the `apiKey` value with your own key from [OpenWeatherMap](https://openweathermap.org/api):

```javascript
const apiKey = "your_api_key_here";
```

### 3. Open in browser

Just open `index.html` directly in your browser — no server needed!

```bash
open index.html   # macOS
```

---

## Project Structure

```
Weather-app-master/
├── index.html         # Main app file
├── style.css          # Styling
├── images/
│   ├── search.png
│   ├── clouds.png
│   ├── clear.png
│   ├── rain.png
│   ├── drizzle.png
│   ├── mist.png
│   ├── humidity.png
│   └── wind.png
└── README.md
```

---

## License

This project is open source and available under the [MIT License](LICENSE).

---

## Author

Built by [shivaraj-dev-codes](https://github.com/shivaraj-dev-codes) 
