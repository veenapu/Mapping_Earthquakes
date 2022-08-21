# Mapping_Earthquakes
# Module 13: Mapping Earthquakes with JS and APIs

## Background
View the earthquake data in relation to the tectonic plates’ location on the earth, and see all the earthquakes with a magnitude greater than 4.5 on the map, and see the data on a third map.

## Deliverable 1: Add Tectonic Plate Data
- The tectonic plate data is added as a second layer group
- The tectonic plate data is added to the overlay object
- The d3.json() callback is working and does the following:
  .The tectonic plate data is passed to the geoJSON() layer
  .The geoJSON() layer adds color and width to the tectonic plate lines
  .The tectonic layer group variable is added to the map
- The earthquake data and tectonic plate data displayed on the map when the page loads

![Tectonic_Plate](https://github.com/veenapu/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/Earthquake_%26_Tectonic_Plate.PNG)

## Deliverable 2: Add Major Earthquake Data
- The major earthquake data is added as a third layer group
- The major earthquake data is added to the overlay object
- The d3.json() callback is working and does the following:
  . Sets the color and diameter of each earthquake.
  . The major earthquake data is passed to the geoJSON() layer.
  . The geoJSON() layer creates a circle for each major earthquake, and adds a popup for each circle to display the magnitude and location of the 	earthquake
  .The major earthquake layer group variable is added to the map
- All the earthquake data and tectonic plate data are displayed on the map when the page loads and the datasets can be toggled on or off

![Major_Earthquakes](https://github.com/veenapu/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/With_Major_Earthquakes.PNG)

## Deliverable 3: Add an Additional Map
- A third map tile layer is created
- The third map is added to the overlay object
- All the earthquake data and tectonic plate data are displayed on the all maps of the webpage

![Tectonic_Plate_and_Two_Earthquakes](https://github.com/veenapu/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/Tectonic_Plate_%26_Two_Earthquakes.PNG)