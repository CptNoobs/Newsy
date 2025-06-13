# Sample News Globe

This project places news headlines on a 3D globe. It was adapted from the original "globe of extremes" demo and uses the ArcGIS API for JavaScript.

Click anywhere on the globe to fetch the latest headline for that location. The reverse geocoder at `geocode.arcgis.com` determines the country and then the app requests the top article from [NewsAPI](https://newsapi.org/). If the request fails, a headline from `sample-news.geojson` is used instead.

Add your NewsAPI key in `index.html` (see the `NEWS_API_KEY` constant), then serve the directory with any static web server and open `index.html` in your browser.
