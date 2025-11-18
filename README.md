🌦️ Weather Forecast Web App

A modern, responsive weather application built with HTML, CSS, JavaScript, and WeatherAPI.
This project provides real-time weather updates, automatic location tracking, and a clean glass-blur UI with a live background video.

🚀 Features
✅ Real-Time Weather by User Location

Automatically detects the user’s current GPS location using the browser’s Geolocation API.

Fetches live weather data based on latitude & longitude.

Displays:

Temperature

Weather condition

Wind speed

Humidity

Cloud cover

UV Index

Visibility

Pressure

Date & time

🔍 City-Based Weather Search

Users can manually enter any city to view its weather information:

Instant search

Auto-updates all weather detail sections

Displays country, local time, weather status, and icons

🎬 Dynamic Glass-Blur UI With Background Video

A modern UI built with glassmorphism:

Frosted glass panels

Soft blur using backdrop-filter

Smooth rounded corners

Full-screen autoplay background video

High readability with an optional overlay

🌅 Sunrise & Sunset Times

Displays accurately:

Sunrise time

Sunset time
based on the selected city or current location.

🌦️ Modern Icons for Weather Conditions

Weather icons change dynamically depending on:

Rain

Cloud

Fog

Clear sky

Night/day conditions

📱 Fully Responsive

Optimized for:

Desktop

Tablet

Mobile

All components scale smoothly with CSS flexbox.

🛠️ Technologies Used

HTML5

CSS3 (Glassmorphism + animations)

JavaScript (ES6)

WeatherAPI – current & forecast endpoints

Browser Geolocation API

Background video (MP4)

🔧 API Integration

Weather data fetched from:

http://api.weatherapi.com/v1/current.json
http://api.weatherapi.com/v1/forecast.json?days=1


Includes:

Current weather

Hourly weather

Sunrise / sunset

Local time

📂 Project Structure
/assets
   /image  -> Icons, weather icons
   /video  -> Background video
index.html
script.js
style.css
README.md

▶️ How to Run the Project

Clone the repo:

git clone https://github.com/your-username/weather-app.git


Open the project folder:

cd weather-app


Open index.html in your browser.

No backend required — fully frontend-based.

🔑 Environment Variables (Optional)

If you want to hide your API key, create:

config.js


Inside:

const API_KEY = "your-weatherapi-key";


Then import it in your script.

📌 To-Do (Future Improvements)

3-day or 7-day forecast

Animated weather backgrounds

Dark mode toggle

Save last searched city

Weather alerts

🤝 Contributing

Fork the repo, make your changes, and submit a pull request.

📸 UI Preview
<img width="1916" height="760" alt="image" src="https://github.com/user-attachments/assets/4eeade56-cd11-4f51-877d-f738cdefabc1" />
