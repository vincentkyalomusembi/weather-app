# React + Vite

# 🌦️ Weather App

A simple weather app built using **React + Vite** that allows users to search for the current weather in any city using data from the **OpenWeather API**.

 ![image](https://github.com/user-attachments/assets/7d0a96b7-24c5-4c44-95e8-037eb04b3282)


## 🚀 Live Demo

👉 [View it on Vercel](https://weather-app-three-rho-63.vercel.app/)

## 🔧 Features

- Search weather by city name
- Real-time temperature, humidity, and wind speed
- Beautiful weather icons based on condition
- Responsive design for mobile and desktop

## 🧪 Technologies Used

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [OpenWeather API](https://openweathermap.org/api)
- CSS / Tailwind (if used)

## 📦 Getting Started Locally

1. **Clone the repo**:

git clone https://github.com/vincentkyalomusembi/weather-app.git
cd weather-app
    Install dependencies:

npm install

    Set up environment variable:

Create a .env file:

VITE_APP_ID=your_openweather_api_key

    Run the app:

npm run dev

Open http://localhost:5173 in your browser.
🌐 Deployment

This project is deployed using Vercel. To deploy:

    Push your project to GitHub

    Go to vercel.com

    Import your GitHub repo

    Add your VITE_APP_ID as an environment variable

    Click Deploy

📝 Notes

    Temperature values from the API are in Kelvin. You can convert to Celsius using:

const celsius = kelvin - 273.15;

    Wind speed comes in m/s; to get km/h, multiply by 3.6.

🧑‍💻 Author

    Vincent Kyalo Musembi

    (https://github.com/vincentkyalomusembi)

⭐️ Show your support

If you're learning and improving, give this project a ⭐ on GitHub!


---

### 📌 To use this README:

1. **Create a `README.md`** file in your project folder:
   ```bash
   touch README.md
