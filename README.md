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
 <br>
- Getting my geolocation button to work

<br>

<p> I was able to explore JavaScript DOM and i hope to implement it in my future projects </p>

<h4> HOW TO USE</h4>
- Open https://adimchi-weather-app.netlify.app/
<br>
- Input city and click enter or

<br>
- Use the second button to get weather information in your current city

<h4> Some code i'm proud of:</h4>


```JS
function getCurrentLocation(event) {
  event.preventDefault();
  navigator.geolocation.getCurrentPosition(searchLocation);
}
```
```CSS
.foot-note{
    margin: 0 auto;
    display: block;
    text-align: center;
}
```
```HTML
<h1  class="temp" ><strong id="temperature"></strong><small>°</small><small id="units"><a href="#"><span id="celsius-link" class="active">C</span></a>|<a href="#"><span class="active" id="fahrenheit-link">F</span></a></li></small>
                 </h1>
```

<h4>SCREENSHOT</h4>
![Screenshot 2022-04-01 at 15-04-24 weather](https://user-images.githubusercontent.com/74629257/171854858-45f92282-c0c2-469e-9f7c-c4bcbe48e1f3.png)


