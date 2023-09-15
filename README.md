 Leaflet.js and Python API
 -----
 In this example, I use live data from the Citi Bike API to create a Leaflet map that displays the locations of Citi Bike stations in New York and their current bike capacity.


Deployment:
-------
https://kristianrafuse.github.io/CityBike/


Highlights:
-------
* Perform an API call to the Citi Bike API to get the station information.
* Pull the "stations" property from response.data.
* Initialize an array to hold the bike markers.
* Loop through the stations array and for each station, create a marker, and bind a popup with the station's name
* Create the tile layer that will be the background of our map.
* Create a baseMaps object to hold the lightmap layer.
* Create an overlayMaps object to hold the bikeStations layer.
* Create a layer control, and pass it baseMaps and overlayMaps. Add the layer control to the map.