# Leaflet Visualizing Data with Leaflet

## Background

![1-Logo](Images/1-Logo.png)

The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. 
This app consists of an imported GeoJSON from the USGS API

![2-BasicMap](Images/2-BasicMap.png)

![3-Data](Images/3-Data.png)

The USGS provides earthquake data in a number of different formats, updated every 5 minutes. [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php).

   ![4-JSON](Images/4-JSON.png)

Mapping using Leaflet that plots all of the earthquakes based on their longitude and latitude, data markers reflect the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes appear larger and darker in color. Popups provide additional information about the earthquake when a marker is clicked.
Two data sets into two separate overlays that can be turned on and off independently.
