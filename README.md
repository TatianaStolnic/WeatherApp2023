# WeatherApp2023
last project
android_develop_final_project
my first android app - WeatherApp23

This WeatherApp23 application has two activities (MainActivity and forecastActivity).
Navigating between the 2 screens: go to showForecastActivity by clicking Button, return to MainActivity by clicking Button-BACK.
MainActivity displays some data (city, temperature, wind speed, weather description) taken from 
https://api.openweathermap.org/data/2.5/weather?q=tampere&units=metric&appid=6c433438776b5be4ac86001dc88de74d , 
forecastActivity displays some data (city, back button) that directs to the main page.
Activity data is not lost during the activity lifecycle, such as when you rotate the device or back out of email/call apps.
All strings are localized in English, Italian and Romanian.
There are no hard-coded strings.
