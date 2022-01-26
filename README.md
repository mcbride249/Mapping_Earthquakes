# Mapping_Earthquakes


![Summary - Image 1](https://user-images.githubusercontent.com/92111396/151264994-97cc03b9-63dc-413e-a53e-ffd50afa68b7.png)


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Project Overview**

The purpose of this project was to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days. To complete this task, we used a URL for GeoJSON earthquake data from the USGS website and retrieved the geographical coordinates and magnitudes of earthquakes for the last seven days and used JavaScript and the D3.js library to plot this data visually. The Leaflet library was used to plot the data on a Mapbox map through an API request that allowed for the visual creation and interaction of the earthquake data.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Resources**

-Data Source: tectonic_plate_starter_code.js; major_earthquake_chart_starter_code; https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson; https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson.

-Software: Python 3.7.10, Visual Studio Code, 1.38.1.

-Resources: https://docs.mapbox.com/; https://earthquake.usgs.gov/earthquakes; https://github.com/fraxen/tectonicplates

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Module 13 - Challenge** 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Purpose**

The purpose of this assignment was to create an earthquake map with edifferent overlays which displayed the the earthquake data in relation to the tectonic plates' location on the earth, particularly those earthquakes with a magnitude greater than 4.5.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Results**

**Deliverable 1: Add Tectonic Plate Data**

![Deliverable 1 - Image 1](https://user-images.githubusercontent.com/92111396/151263132-8d9c0e73-44c9-4222-b5b3-e6aadcb2c1fb.png)

This above image illustrates the "Streets" overlay with both the "Earthquakes" and "Tectonic Plates" data displayed.


![Deliverable 1 - Image 2](https://user-images.githubusercontent.com/92111396/151263399-1dd342f4-b450-4f01-a44e-e63c23363bba.png)

This above image illustrates the "Satellite" overlay with only the "Tectonic Plates" data displayed.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Deliverable 2: Add Major Earthquake Data**

![Deliverable 2 - Image 1](https://user-images.githubusercontent.com/92111396/151263750-a51c8627-fd08-4655-a92d-1009888eb609.png)

This above image illustrates the "Streets" overlay with only the "Major Eathquakes" data displayed.


![Deliverable 2 - Image 2](https://user-images.githubusercontent.com/92111396/151263775-f6a61597-e53c-4007-8f86-1f4e646e2393.png)

This above image illustrates the "Satellite" overlay with both the "Major Earthquakes" and "Tectonic Plates" data displayed.


----------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Deliverable 3: Add an Additional Map**

A new "Dark" overlay was created as an additional map. This dark overlay created an issue where some of the major earthquake data could not be displayed due to colour contrast, so the colour was changed from black to purple.  

![Deliverable 3 - Image 1](https://user-images.githubusercontent.com/92111396/151264035-3c44ff59-b2e5-4e76-a0aa-54e386db52d4.png)

This above image illustrates the "Dark" overlay with both the "Earthquakes", "Major Earthquakes" and "Tectonic Plates" data displayed.


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Summary**

The data was able to be displayed correctly for "Earthquakes", "Major Earthquakes" and "Tectonic Plates". A new "Dark" overlay was successfully created and overlays and data projections functioned correctly.


![Summary - Image 2](https://user-images.githubusercontent.com/92111396/151265014-9ab77f3d-341d-4b3f-b8e7-d539560dfe32.png)




