# Mapping_Earthquakes
Code Version 1.0

## Project Overview
This project has the propose of gather different earthquake maps and views of tectonic plates locations on the earth, all of this view are designed with GeoJSON data from the USGS API, and include a dynamic view with selector menu that allow to change in easy way the view according to each magnitude.

## Results 
In the first view we get tectonic plate data using d3.json(), add the data using the geoJSON() layer, set the tectonic plate Line String data to stand out on the map, and embedded tectonic plate data to the overlay object with the earthquake data.

   #### Tectonic plate 
   ![](https://github.com/JulioAQuintana/Mapping_Earthquakes/blob/main/Resources/MajorEQ.png)

also include a major earthquake data to the map using d3.json(). included color and set the radius of the circle markers based on the magnitude of earthquake, and add a popup marker for each earthquake that displays the magnitude and location of the earthquake using the GeoJSON layer, geoJSON().

   #### Major earthquake data
   ![](https://github.com/JulioAQuintana/Mapping_Earthquakes/blob/main/Resources/TectonicPlates.png)

third map style to earthquake map.
   #### Dark map view
   ![](https://github.com/JulioAQuintana/Mapping_Earthquakes/blob/main/Resources/dark.png)

## Resources 
-Data Source: Earthquakes GeoJSON,Tectonic Plate GeoJSON and Earthquakes above 4.5mag GeoJSON
-Software tools and programming language: HTML/CSS, JavaScript Visual Studio Code,Leaflet 1.7.1 and D3.js 6.2.0

Finally, feel free to take reference into the code by interactive Maps Webpage file located in the next link
   #### (https://github.com/JulioAQuintana/Election_Analysis)
