# Mapping_Earthquakes-

## Overview of the Project

In this project, we will be gathering earthquake GeoJSON data from the USGS APIs,  and  then creating and exploring interactive maps of earthquakes around the world.
The earthquake data is represented on the maps in relation to the tectonic plates’ location on the earth, and according to each event magnitude.

### Resources

#### Software

• Javascript

• HTML/CSS

• VS Code

• Jupyter Notebook

• ECMAScript

• MapBox APIs

• Leaflet

#### Data Source

• tectonic_plate_starter_code

• major_earthquake_starter_code

• majorAirports.json

• torontoNeighborhoods.json

• torontoRoutes.json

## Results

#### Tectonic Plate Data

In this deliverable, we have added the  tectonic plate data using d3.json()as well as the data using the geoJSON() layer, and then set the tectonic plate LineString data to stand out on the map, and finally we have added the tectonic plate data to the overlay object with the earthquake data. We were able to do that using Javascript, Leaflet.js and geoJSON data.

##### Views

• Street

<img width="1672" alt="Earthquake_Tectonic_Street_View" src="https://user-images.githubusercontent.com/107282754/191815398-82613604-b9fd-47f3-99f1-c4c876cdd044.png">

• Satellite

<img width="1646" alt="Earthquake_Tectonic_Satellite_View" src="https://user-images.githubusercontent.com/107282754/191815479-5e3c6694-b6ce-47b7-8bdf-4dab611ce1b4.png">

#### Major Earthquake

Using  JavaScript, Leaflet.js, and geoJSON data, we have added major earthquake data to the map using d3.json() and we also have  added color and set the radius of the circle markers based on the magnitude of earthquake, and finally, we added a popup marker for each earthquake to displays the magnitude and location of the earthquake using the GeoJSON layer, geoJSON().

##### Views

• Street

<img width="1671" alt="Earthquake_Tectonic_Major_Street_View" src="https://user-images.githubusercontent.com/107282754/191815625-24ae7e82-91e7-47e0-84a9-143389481bab.png">

• Satellite

<img width="1673" alt="Earthquake_Major_Satellite_View" src="https://user-images.githubusercontent.com/107282754/191815663-49d19563-ebf0-4633-90ae-d281c9b5ac4e.png">

#### Additional Map
 
We have used JavaScript and Leaflet.js, in this deliverable to add a third map style to the earthquake map.

• Earthquake_Tectonic_Dark_View

<img width="1666" alt="Earthquake_Tectonic_Dark_View" src="https://user-images.githubusercontent.com/107282754/191815537-f072f4ea-5411-4028-a30a-82995b4df4b2.png">

• Earthquake Major Dark View

<img width="1663" alt="Earthquake_Major_Dark_View" src="https://user-images.githubusercontent.com/107282754/191815720-df6857c3-5d88-41b6-9b17-f953eda9b719.png">
