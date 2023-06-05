# Visualizing Data with Leaflet

Deployment Link: https://olenafedorenko.github.io/leaflet-challenge/

## Introduction
This project utilizes leaflet, Javascript and D3 to visualize the earthquake data from the United States Geological Survey (USGS). The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

<h2 align="center">
 The Earthquake Visualization
  </h1>
  
  
### Get the Data Set
- The USGS provides earthquake data in a number of different formats, updated every 5 minutes
- The "All Earthquakes from the Past 7 Days" data set was selected from the [USGS GeoJSON Feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page
- The data was given in JSON format which was used to pull in the data for the visualization

### Import and Visualize the Data
Create a map using Leaflet that plots all of the earthquakes from the data set based on their longitude and latitude.
- The data markers reflect the magnitude of the earthquake by their size and and depth of the earth quake by color
- Earthquakes with higher magnitudes appear larger and earthquakes with greater depth should appear darker in color
- Popups that provide additional information about the earthquake were included when a marker is clicked
- A legend was created to provide context for the map data

## Results
USGS All Earthquakes for the Past Week

<p align ="center">
  <img src="https://github.com/olenafedorenko/leaflet-challenge/blob/main/Images/map.png">
</p>

