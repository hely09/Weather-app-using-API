# 🌦️ Weather App

A simple and responsive Weather Application built using **HTML, CSS, and JavaScript** that fetches real-time weather data using the **OpenWeatherMap API**.

---

## 🚀 Features

* 🌍 Search weather by city name
* 🌡️ Displays temperature in Celsius
* 💧 Shows humidity level
* 🌬️ Displays wind speed
* 🌤️ Dynamic weather icons (Clouds, Clear, Rain, Drizzle, Mist)
* ❌ Error handling for invalid city names
* 📱 Responsive and clean UI

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (Vanilla JS)
* OpenWeatherMap API

---

## 📂 Project Structure

```
Weather-App/
│
├── index.html
├── style.css
├── images/
│   ├── clear.png
│   ├── clouds.png
│   ├── drizzle.png
│   ├── humidity.png
│   ├── mist.png
│   ├── rain.png
│   ├── snow.png
│   ├── wind.png
│   └── search.png
```

---

## ⚙️ How It Works

* User enters a city name
* App sends request to OpenWeather API
* Displays:

  * City name
  * Temperature
  * Humidity
  * Wind speed
* Updates weather icon based on condition

---

## 🔑 API Integration

This app uses OpenWeatherMap API:

```javascript
const apiKey = "YOUR_API_KEY";
const apiUrl = "https://api.openweathermap.org/data/2.5/weather?units=metric&q=";
```

👉 Replace `YOUR_API_KEY` with your own API key.

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/weather-app.git
```

2. Open folder

```bash
cd weather-app
```

3. Run the app

* Open `index.html` in your browser

---

## 📸 Preview

Simple UI with search bar and weather details card.

---

## ⚠️ Known Issues

* API key is exposed in frontend (not secure for production)
* Only basic weather conditions handled

---

## 💡 Future Improvements

* Add forecast (5-day weather)
* Add location-based weather (GPS)
* Improve UI animations
* Add dark/light mode toggle

---

## 🙌 Acknowledgement

* Weather data provided by **OpenWeatherMap**

---

## 📌 Author

**Hely Vachhani**

* GitHub: https://github.com/hely09
