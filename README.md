#Leaflet.GoogleAutocomplete
Adds support for address lookup (a.k.a. geocoding / geoseaching) to Leaflet with Google Places Javascript library.

#Using the control

Create the map and add the control:

````
var map = L.map('map').setView([51.505, -0.09], 13);
var googleLayer = new L.Google('ROADMAP');
map.addLayer(googleLayer);

new L.Control.GoogleAutocomplete().addTo(map);
````
