# Mapping_Earthquakes
# Project Overview
For this project I created an earthquake map with two different base maps and the earthquake overlay. Now, Basil and Sadhana would like to see the earthquake data in relation to the tectonic plates’ location on the earth, and they would like to see all the earthquakes with a magnitude greater than 4.5 on the map, and they would like to see the data on a third map.

# Tools
- VS Code<br/>
- HTML/CSS<br/>
- JavaScript<br/>
- Leaflet.js<br/>
- GeoJSON data

# Results
### 1. Tectonic Plates
The first part of this challenge includes improving the map by adding tectonic plate data using d3.json() as below:<br/>
- The tectonic plate data is added as a second layer group<br/>
- The tectonic plate data is added to the overlay object<br/>
- The d3.json() callback does the following:<br/>
  - The tectonic plate data is passed to the geoJSON() layer
  - The geoJSON() layer adds color and width to the tectonic plate lines
  - The tectonic layer group variable is added to the map
![Del1_code.png](https://github.com/rmat112/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/Del1_code.png)

- The earthquake data and tectonic plate data displayed on the map when the page loads 
![Del1_final.png](https://github.com/rmat112/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/Del1_final.png)

### 2. Major Earthquake Data
The next improvement is to add major earthquake data to the map using d3.json() as below:<br/>
- The major earthquake data is added as a third layer group
- The major earthquake data is added to the overlay object
![Del2_code(1).png](https://github.com/rmat112/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/Del2_code(1).png)
- The d3.json() callback is working and does the following:
  - Sets the color and diameter of each earthquake.
  - The major earthquake data is passed to the geoJSON() layer
 ![Del2_code(2).png](https://github.com/rmat112/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/Del2_code(2).png)
  - The geoJSON() layer creates a circle for each major earthquake, and adds a popup for each circle to display the magnitude and location of the earthquake
  - The major earthquake layer group variable is added to the map
![DEL2_code(3).png](https://github.com/rmat112/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/DEL2_code(3).png)

- All the earthquake data and tectonic plate data are displayed on the map when the page loads and the datasets can be toggled on or off

![Del2_final.png](https://github.com/rmat112/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/Del2_final.png)


### 3. Third Base Map
Finally, using the options from the Mapbox styles, a third map style is added as a tile layer object to the challenge_logic.js file and the map variable is added to the base layer object.
![Del3_code.png](https://github.com/rmat112/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/Del3_code.png)

All the earthquake data and tectonic plate data are displayed on the all maps of the webpage (5 pt)
![Del3_base3.png](https://github.com/rmat112/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/Del3_base3.png)
# Summary
