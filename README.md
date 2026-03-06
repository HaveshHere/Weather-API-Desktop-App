# 🌦️ Weather API Desktop App

A simple PyQt5 desktop application that retrieves and displays real-time weather information using the OpenWeather API. Users can enter a city name to view the current temperature, weather description, and a matching weather emoji.

## ✨ Features

- Search weather by city name
  
- Displays temperature in **Celsius**
  
- Shows weather condition description
  
- Displays a weather emoji based on weather type
  
- Handles API and connection errors gracefully
  
- Clean graphical user interface built with PyQt5  

## 🔗 API Used

This project uses the **OpenWeather Current Weather API**.

API request format:

https://api.openweathermap.org/data/2.5/weather?q={city}&appid={api_key}

## 🖥️ How the Application Works

1. The user enters a city name in the input field.
   
2. Clicking **Get Weather** sends a request to the OpenWeather API.
   
3. The application receives weather data in JSON format.
   
4. The program extracts:
   
  - temperature
     
  - weather description
     
  - weather condition ID
     
5. The temperature is converted from **Kelvin to Celsius** and displayed along with a corresponding weather emoji.
   
6. If the request fails, an error message is displayed.

## 📚 What I Learned

This project helped me learn how to integrate external APIs into Python applications, build desktop interfaces using PyQt5, process JSON data, and implement error handling to create a functional real-time application.

## 🚀 Future Improvements

- Add humidity and wind speed display

- Support temperature unit selection (Celsius/Fahrenheit)
- Add weather icons instead of emojis

- Include a 5-day weather forecast

- Improve the graphical interface design

## 🎥 Video

https://github.com/user-attachments/assets/765dd120-591f-4012-845c-3f84ad911fb3
