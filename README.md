# Hunger-games
 <h2> Overview</h2>
<p> Get accurate weather information, temperature in celsius and fahrenheit, wind speed, humidity, weather description, minimum and maxximum temperature, and a 6 day forecast in your current location among other cities in the world. </p>
<br>
<h3>Built with:</h3>
<ul>
 <li>HTML</li>
  <li>CSS</li>
  <li>Bootstrap</li>
  <li>JavaScript</li>
 <li>DOM</li>
 <li>APIs</li>
 </ul>
 
<h4>Challenges Faced:</h4>
- This was my first time using APIs and i had a hard time fetching, but i used axios and it made my work easier.
- Getting my geolocation button to work
<p> I was able to explore JavaScript DOM and i hope to implement it in my future projects </p>

<h4> HOW TO USE</h4>
- Open https://adimchi-weather-app.netlify.app/
- Input city and click enter or
- Use the second button to get weather information in your current city

<h4> Some code i'm proud of</h4>
```JS
function getCurrentLocation(event) {
  event.preventDefault();
  navigator.geolocation.getCurrentPosition(searchLocation);
}
```




