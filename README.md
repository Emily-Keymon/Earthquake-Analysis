## Website:   https://emily-keymon.github.io/Earthquake-Analysis/

----

# Earthquake Analysis

The goal of this project was to use JavaScript to present an interactive map visualization of USGS earthquake data within a web page. Leaflet was used to import and process the data, as well as generate the required visualization. Mapbox was used to create a map that plots all of the earthquakes from the data set based on their longitude and latitude. Then, a second data set was plotted on the map to illustrate the relationship between tectonic plates and seismic activity.

---

The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and pick a data set to visualize. When you click on a data set, for example 'All Earthquakes from the Past 7 Days', you will be given a JSON representation of that data. You will be using the URL of this JSON to pull in the data for the visualization.

---
## Datasets
* https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php
* https://github.com/fraxen/tectonicplates


---
## Tools Used
* PyCharm - Python IDE
* JavaScript - d3, Leaflet
* HTML, CSS, Bootstrap
* Mapbox

---
## Tasks
### Level 1: Basic Visualization
1.  Create the tile layer that will be the background of the map
2.  Create the map object with options
3.  Add 'graymap' tile layer to the map
4.  Get dataset by making an AJAX call that retrieves earthquake geoJSON data
5.  Function to return style data for each of the earthquakes plotted on the map
6.  Function to determine color of the marker based on the magnitude of the earthquake
7.  Function to determine radius of the earthquake marker based on its magnitude
8.  Add a GeoJSON layer to the map once the file is loaded
9.  Turn each feature into a circleMarker on the map
10.  Set the style for each circleMarker using styleInfo function
11.  Create a popup for each marker to display the magnitude and location of the earthquake after the marker has been created and styled
12.  Add to map
13.  Create a legend control object
14.  Add all the details for the legend
15.  Loop through intervals to generate a label with a colored square for each interval
16.  Add legend to the map



### Level 2: More Data
1.  Create the tile layers that will be the selectable backgrounds of the map
2.  Grayscale layer
3.  Satellite layer
4.  Outdoors layer
5.  Create the map object with options, add layers created above
6.  Add 'graymap' tile layer to the map
7.  Create layers for two different sets of data, earthquakes and tectonicplates
8.  Define an object that contains all of the different map choices
9.  Define an object that contains all of the overlays
10. Add a control to the map to allow user to change which layers are visible
11. Get dataset by making an AJAX call that retrieves earthquake geoJSON data
12. Function to return style data for each of the earthquakes plotted on the map
13. Function to determine color of the marker based on the magnitude of the earthquake
14. Function to determine radius of the earthquake marker based on its magnitude
15. Add a GeoJSON layer to the map once the file is loaded
16. Turn each feature into a circleMarker on the map
17. Create a popup for each marker to display the magnitude and location of the earthquake after the marker has been created and styled
18. Add to earthquake layer (instead of directly to the map)
19. Add earthquake layer to map
20. Create a legend control object
21. Add all the details for the legend
22. Loop through intervals to generate a label with a colored square for each interval
23. Add legend to the map
24. Get dataset by making an AJAX call that retrieves tectonic plate geoJSON data
25. Add geoJSON data and style information to the tectonicplates layer
26. Add the tectonicplates layer to map
    
 ---
## Results
### Grayscale
![grayscale](https://user-images.githubusercontent.com/64673015/112073528-4fed8280-8b42-11eb-8f6c-76ac7f8e5aa9.PNG)

### Outdoors
![outdoors](https://user-images.githubusercontent.com/64673015/112073581-6bf12400-8b42-11eb-9d68-7318545a50bd.PNG)

### Satellite
![satellite](https://user-images.githubusercontent.com/64673015/112073648-875c2f00-8b42-11eb-81eb-d171c0b55fd7.PNG)

---

