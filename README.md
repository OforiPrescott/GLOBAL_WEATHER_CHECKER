# GLOBAL_WEATHER_CHECKER
Global weather app was built in HTML, CSS and Javascript(Vanilla)

In this weather app, you can get the weather details of a particular city by entering the city name or you can also get your current location weather details by clicking on the “Get Device Location” button. If you entered an invalid city name then there is shown an error message.

You’ll get many weather details in this app like temperature in celsius, weather conditions, location, feels like, and humidity.

Also, I used OpenWeatherMap API to get the weather details of the user entered city or user’s current location.

In the JavaScript file, I got the user entered city name and sent a get request to an OpenWeatherMap API with passing the city name. If the user clicked on the “Get Device Location” button then first I checked the user browser supports geolocation API or not.

If it’s supported, I got the current latitude and longitude of the device and sent these coordinates to the OpenWeatherMap API. After I got an object as a response from the API then I displayed the property value to a particular HTML element. At last, using the id value that API provides us, I showed the custom weather icon/image according to the weather condition.

Finally, in the UI I got an animated video from Lottifiles and used for the background. It's seen as "weather.gif" when going through the CSS codes.
