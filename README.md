<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Weather Dashboard</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="weather-dashboard">
    <h1>Weather Dashboard</h1>
    <div class="search">
      <input type="text" id="city" placeholder="Enter city name" />
      <button onclick="getWeather()">Get Weather</button>
    </div>
    <div id="weather-data">
      <h2 id="city-name"></h2>
      <p id="temperature"></p>
      <p id="weather-description"></p>
      <img id="weather-icon" src="" alt="Weather Icon">
      <p id="forecast"></p>
    </div>
  </div>
  <script src="app.js"></script>
</body>
</html>
