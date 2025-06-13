# Sample News Globe

This project places news headlines on a 3D globe. It was adapted from the original "globe of extremes" demo and uses the ArcGIS API for JavaScript.

Click anywhere on the globe to fetch the latest headline for that location. The reverse geocoder at `geocode.arcgis.com` determines the country and then the app requests the top article from [NewsAPI](https://newsapi.org/). If the request fails, a headline from `sample-news.geojson` is used instead.

Add your NewsAPI key in `index.html` (see the `NEWS_API_KEY` constant). If you don't have a key, the globe will still work using the bundled sample data.

To preview the site locally, start a simple web server such as `npx serve` or `python3 -m http.server`, then open `index.html` in your browser.
