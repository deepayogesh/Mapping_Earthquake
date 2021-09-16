# Populate Interactive Geographical  maps for Data visualizations and explore earthquakes around the world. 

## Purpose 
This project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days. 

### Steps  
In this project, I use a URL for GeoJSON earthquake data from the USGS website and retrieve geographical coordinates and the magnitudes of earthquakes for the last seven days. Then added the data to a map.

### Display
Using  the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. I used the Leaflet library to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.

## Geographical Features used for visualizations 
- Points, which conatains addresses and location like lattitude and Longitude coordinates.
- Line strings which conatains coordinates for the boundries of the streets, highways, travle routes and tectonic plates
- Polygon which conatains coordinates fr the boundries of the zipcodes, counties, countries and provience, 
and tracts of land 
- Use of JavaScript D3 and Leaflet library and map box API
- Use JavaScript ES6 functions to add GeoJSON data, features, and interactivity to maps

### Earthquake data 
Each earthquake will be visually represented by a circle and color, where a higher magnitude will have a larger diameter and will be darker in color. In addition, each earthquake we have a popup marker that, when clicked, will show the magnitude of the earthquake and the location of the earthquake.

### Tectonic Plate 
Tectonic plate data retrived from URL. Lines are displayed in orange color. Using layer control the second map. 

### Major Earthquake 
Each Major earthquake will be visually represented by a circle and color, where a higher magnitude will have a larger diameter and will be darker in color. In addition, each earthquake we have a popup marker that, when clicked, will show the magnitude of the earthquake and the location of the earthquake.
Legend displayed in the bottom right corner. 

## Summary 
Populated a geographical map with GeoJSON earthquake data from a URL with the help of d3 and Leaflet labrary of javascript and made interactive using MAPBOX API. Use JavaScript ES6 functions to add GeoJSON data, features, and interactivity to maps. Multiple map layers to geographical maps using Leaflet control plugins to add user interface controls.
