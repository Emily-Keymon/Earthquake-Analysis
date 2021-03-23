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



2. **Import & Visualize the Data**

   Create a map using Leaflet that plots all of the earthquakes from the data set based on their longitude and latitude.

   * The data markers should reflect the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes should appear larger and darker in color.

   * Include popups that provide additional information about the earthquake when a marker is clicked.

   * Create a legend that will provide context for the map data.


### Level 2: More Data

The USGS wants you to plot a second data set on the map to illustrate the relationship between tectonic plates and seismic activity. Pull in a second data set and visualize it along side the original set of data. Data on tectonic plates can be found at <https://github.com/fraxen/tectonicplates>.

* Plot a second data set on the map.

* Add a number of base maps to choose from as well as separate out the two different data sets into overlays that can be turned on and off independently.

* Add layer controls to the map.

---
## Results
### Grayscale
![grayscale](https://user-images.githubusercontent.com/64673015/112073528-4fed8280-8b42-11eb-8f6c-76ac7f8e5aa9.PNG)

### Outdoors
![outdoors](https://user-images.githubusercontent.com/64673015/112073581-6bf12400-8b42-11eb-9d68-7318545a50bd.PNG)

### Satellite
![satellite](https://user-images.githubusercontent.com/64673015/112073648-875c2f00-8b42-11eb-81eb-d171c0b55fd7.PNG)

---

