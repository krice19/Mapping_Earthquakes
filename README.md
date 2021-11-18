# Mapping_Earthquakes

## About the Project

This project will analyze Earthquake data that will be used to create map visualizations.   The final visualization will be a map with 3 layers: one layer with tectonic plate data, one layer with Major Earthquake data, and one layer for major earthquakes with high magnitudes.  The location of the earthquakes are mapped with a circle, which differs in radius and color depending on magnitude.  The final visualization will also include 3 map styles to choose from: street, satellite street, and dark.

### Layer Descriptions

**Tectonic Plate Layer**: The tectonic plate layer is built with LineString geoJSON data.  A layer group variable is created for the tectonic data and the data is called using d3.json().

**Major Earthquake Data**: The Major Earthquake data layer displays the location of major earthquakes on the map as a circle point.  The size and color of the circle is dependent on earthquake magniture, green indicating a magnitude of up to 1 and orange indicating a magniture of 4-5.  When the circle is clicked on the map, a pop up will display the exact magnitude and location of the earthquake.

**High Magnitude Earthquake Data**:  The high magnitude earthquake layer displays a circle point at the location earthquakes with magnitudes greater than 5.  These high magnitude earthquakes will have a radius larger than the other earthquake point and be the color red.  A pop up will also display the exact magnitude and location when the circle point is clicked.

### Built With

- JavaScript
- Leaflet.js
- D3.js
- HTML
- CSS


