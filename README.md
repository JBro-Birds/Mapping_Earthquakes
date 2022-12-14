# Mapping_Earthquakes

## Overview of Project
The project calls for building a HTML map showing geographical coordinates and the magnitudes of earthquakes for the last seven days.  To complete this project, earthquake data will be pulled from a URL for GeoJSON earthquake data from the USGS website via API calls and using JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. The Leaflet library will be used to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.

### Purpose
The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days.  There will be three base maps (streets, satellite and outdoors) and three overlays (all earthquakes, tectonic plates and major earthquakes defined as > 4.5 magnitude).  The end user will have the ability to choose which map and overlay to view based on the coded layer groups and layer controls and there will be a legend showing earthquake magnitude categories. 

## Results
The webpage with multiple base maps, overlays, layer controls and a legend was successfully constructed as shown below:


![map_screenshot](https://raw.githubusercontent.com/JBro-Birds/Mapping_Earthquakes/master/support_images/map_screenshot.png)

Map and overlay choices appear when end user places cursor on upper right overlay image:

![user_control_layers](https://raw.githubusercontent.com/JBro-Birds/Mapping_Earthquakes/master/support_images/user_control_layers.png)

