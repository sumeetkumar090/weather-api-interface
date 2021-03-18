# weather-api-interface

--------
Overview
--------
This RAML spec provides the definition of the Weather API Interface.

The Weather Publication API allows you to query weather by Country and get weather by City and Country.

--------
Examples
----------
- Get weather by city name and country name:

  `http://localhost:8081/api/getWeather/getWeatherByCityAndCountry?cityName=Sydney&countryName=Australia`

- Get cities by country name

  `http://localhost:8081/api/getWeather/getCitiesByCountry?countryName=Australia`
