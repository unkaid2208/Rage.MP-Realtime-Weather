# Rage.MP-Realtime-Weather

Server-sided script, that getting a real weather hourly and sets it in the gta 5 world.



HowTo:

I. Install getJSON: npm install get-json --save

II. Go to https://developer.accuweather.com/ and register as the Developer.

III. To get your new API key, create your WeatherAPP here, https://developer.accuweather.com/user/me/apps
 On the question: "What programming language is your APP written in?" Answer will be: JavaScript.

IV. Go to https://www.accuweather.com/ and find your preferred location on the map or by the search field, for example: Moscow, Russia.
 To set more accurate location to your preferred, click on the nearest point on the map, for me it is Yakimanka, then click on 'Hourly".

V. The URL will look like this: https://www.accuweather.com/en/ru/yakimanka/2515350/hourly-weather-forecast/2515350
  Well, 2515350 is the Location Key that we will use further.
 
VI. Let's assemble your AccuWeather URL: http://dataservice.accuweather.com/forecasts/v1/hourly/1hour/YOUR_LOCATION_KEY?apikey=YOUR_API_KEY

VII. Paste new AccuWeather URL into the script and save it.

Warning! The Trial Version of AccuWeather is limited for 50 requests per day.
