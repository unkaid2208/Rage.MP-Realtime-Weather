# Rage.MP-Realtime-Weather

HowTo:

0. Install getJSON: npm install get-json --save
 0.1 Go to https://developer.accuweather.com/ and register as the Developer.
 0.2. To get your new API key, create your WeatherAPP here, https://developer.accuweather.com/user/me/apps
 On the question: "What programming language is your APP written in?" Answer will be: JavaScript.

1. Go to https://www.accuweather.com/ and find your preferred location on the map or by the search field, for example: Moscow, Russia.
 1.1. To set more accurate location to your preferred, click on the nearest point on the map, for me it is Yakimanka, then click on 'Hourly".

2. The URL will look like this: https://www.accuweather.com/en/ru/yakimanka/2515350/hourly-weather-forecast/2515350
  Well, 2515350 is the Location Key that we will use further.
 
 3. Let's assemble your AccuWeather URL: http://dataservice.accuweather.com/forecasts/v1/hourly/1hour/YOUR_LOCATION_KEY?apikey=YOUR_API_KEY


Warning! The Trial Version of AccuWeather is limited for 50 requests per day.
