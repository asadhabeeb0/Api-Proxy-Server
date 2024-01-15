Build an API Proxy Server - Hide Your API Keys, Rate Limiting & Caching dated Oct 20, 2021 of playlist Node.js Videos channeled Traversy Media


Server used for hiding API keys, rate limiting and caching. This uses the OpenWeather API but you can easily change it to whatever public API you are using


If the public API URL is https://api.openweathermap.org/data/2.5/weather?q={city}&appid={APIkey}
API_BASE_URL = "https://api.openweathermap.org/data/2.5/weather"
API_KEY_NAME = "appid"
API_KEY_VALUE = "YOUR API KEY"


We can add on any other query params as needed when hitting the /api endpoint such as https://yourdomain/api?q=detroit without having to add your key in the client


Add new routes as you see fit
Change rate limiting and caching to desired values
