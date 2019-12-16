# weather-app


I built a weather dashboard application with search functionality to find current weather conditions and the future weather outlook for multiple cities. 

```
As a traveler
I want to see the weather outlook for multiple cities
so that I can plan a trip accordingly
```

How I delivered..

* I Used the [OpenWeather API](https://openweathermap.org/api) to retrieve weather data for cities.

* Used AJAX to hook into the API to retrieve data in JSON format.

* This app runs in the browser and features dynamically updated HTML and CSS powered by jQuery.

* Displays the following under current weather conditions:

  * City

  * Date

  * Icon image (visual representation of weather conditions)

  * Temperature

  * Humidity

  * Wind speed

  * UV index

* Includes a search history so that users can access their past search terms. Clicking on the city name performs a new search that returns current and future conditions for that city. 

* Includes a 5-Day Forecast below the current weather conditions. Each day for the 5-Day Forecast displays the following:

  * Date

  * Icon image (visual representation of weather conditions)

  * Temperature

  * Humidity



## Minimum Requirements Completed

* User can search for weather reports by city using the openweathermap API.

* After searching for a city, the following information is displayed:

  *  Current temperature

  *  Current humidity

  *  Windspeed

  *  Uv index

  *  5 day forecast

* Application uses icons to represent weather conditions.

* Application stores previously searched for cities in localstorage and displays them to the user.

* Application loads last searched city forecast on page load.