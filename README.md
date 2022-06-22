# Mapping_Earthquakes

## Overview

This repository holds earthquake maps with a tectonic plate overlay as well as an overlay showing major earthquakes over 4.5 magnitude. I used the Mapbox API with Leaflet.js and geoJSON data to create the maps.

#### Sources
- The tectonic plate data was sourced from https://github.com/fraxen/tectonicplates. 
- The data for 4.5+ magnitude earthquakes was sourced from the [USGS GeoJSON Summary Feed for the Past 7 Days](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson).

A popup marker that shows the magnitude and location is displayed for each earthquake. The map can be viewed in street, satellite, or dark tile layers: 

![street.png](https://github.com/stephperillo/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Resources/street.png)

![satellite](https://github.com/stephperillo/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Resources/satellite.png)

![dark.png](https://github.com/stephperillo/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Resources/dark.png)

These maps will be helpful for visualizing earthquake data in relation to the location of the earth's tectonic plates.
