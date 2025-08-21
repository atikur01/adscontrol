# AdsControl API

A simple JSON API for retrieving ad configurations.

## Endpoint

You can access the ads data at:

➡️ [https://adscontrol.onrender.com/ads.json](https://adscontrol.onrender.com/ads.json)

## Usage

Fetch the JSON using **cURL**, **JavaScript**, or any HTTP client.

### Example (JavaScript Fetch)
```js
fetch("https://adscontrol.onrender.com/ads.json")
  .then(response => response.json())
  .then(data => console.log(data))
  .catch(error => console.error("Error:", error));
