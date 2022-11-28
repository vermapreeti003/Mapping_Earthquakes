# Mapping_Earthquakes
### Mapping Earthquakes with JS and API
## Overview
In this project, we used URL for GeoJSON earthquake data, tectonic data and major earthquakes data to retrieve geographical coordinates and magnitudes of earthquakes for the last seven days. Then we have visualized the data on a map.

### Aim
The aim of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days.

## Results
Using JavaScript and Leaflet.js we have created a map that has three styles:

   * Streets View
   * Satellite Streets View
   * Dark View
Using the JavaScript and the D3.js library we have retrieved the coordinates and magnitudes of the earthquakes from the GeoJSON data of the last seven days. We have used Leaflet library to plot the data on a Mapbox map through an API request and created interactive circle markers for the earthquake data:

  * We have color coded the circle markers and modified the radius of the circle based on each earthquake's magnitude.
  * We have added a popup message for each earthquake data.
  * And we have create a legend for the color range of earthquakes.
Following the same concept, we have retrieved major earthquakes data from the GeoJSON Summary Feed for M4.5+Earthquakes for the past 7 days and we have added them to the map.

Moreover, we have retrieved the Tectonic Plate Data from this GitHub repository and we have added them to the map and styled them.

The final map looks like Fig below.


![ssapi](https://user-images.githubusercontent.com/111541268/204306106-95803453-81d3-4af0-91d2-3b98c6db3193.png)


