# qt-weather-desktop-app
Introducing the Qt/C++ based desktop weather forecast app, inspired by the sleek design of the Windows weather app. Dive into real-time weather insights, right at the convenience of your desktop.

## Features

- **Localized Weather Search**: Enter a specific location in the search bar to retrieve tailored weather updates.

  Powered by the REST APIs from [http://t.weather.itboy.net](http://t.weather.itboy.net/api/weather/city/), the app fetches detailed weather stats for cities in China. For instance, for Beijing, the endpoint is http://t.weather.itboy.net/api/weather/city/101010100. Feel free to use tools like Postman to explore the JSON structure from this API.

- **Comprehensive Forecast**: Get a snapshot of the weather trajectory - from yesterday's climate, today's conditions, to forecasts for the next four days.

- **Detailed Metrics**: The app provides more than just temperatures. Delve into specifics such as current weather conditions, wind speed and direction, humidity levels, PM2.5 concentrations, and overall air quality.

### Screenshot

![image-20231007165027690](C:\Users\zzhez\AppData\Roaming\Typora\typora-user-images\image-20231007165027690.png)

### Reflections

Qt serves as an outstanding platform for crafting cross-platform GUI applications compatible with a diverse range of software and hardware. Constructing a weather forecast application offers a concise demonstration of Qt's capabilities. 

For those looking to expand their programming horizons, consider employing Python as an alternative means to replicate this app or even take a leap into the Android domain for a richer learning experience.
