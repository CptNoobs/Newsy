# Sample News Globe

This project places news headlines on a 3D globe. It was adapted from the original "globe of extremes" demo and uses the ArcGIS API for JavaScript.

The file `sample-news.geojson` contains example locations. When you click an orange pin, the app reverse‑geocodes the point and queries the [NewsAPI](https://newsapi.org/) for the latest headline in that country. If the API request fails, the sample text from the GeoJSON file will appear instead.

To view the globe, serve the directory with any static web server and open `index.html` in your browser. Replace `YOUR_NEWSAPI_KEY` in `index.html` with your own key to see live headlines.
