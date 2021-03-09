# Leaflet-Earthquake-Mapping
### Tech Stack
* JavaScript
* Leaflet
* Bootstrap
* CSS
* HTML
- - -
### User Instructions
* Clone the repository: git clone https://github.com/Vincent-glitch/Leaflet-Earthquake-Mapping.git
*  In command: python -m http.server 
*  In web browser: http://localhost:8000/
- - -
# Background
This script utilizes Leaflet to plot all of the earthquakes within the past 7 days. The dataset is a GeoJSON that comes from the [United States Geological Survey](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) (USGS). The location of each earthquake's marker is determined by its longitude and latitude. The color of the marker reflects its magnitude, while the depth for the earthquake is expressed by its size.  Each marker is accompanied by a popup that provides additional information about the earthquake when the marker is clicked. A legend has also been added to the map to provide context for the visualization.
![Screenshot](Resources/earthquake-gif.gif)
