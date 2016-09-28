# RouteMapping
This code is my attempt at mapping GPX data onto various maps (e.g., Google Maps, Open Street Maps, Stamen Map).
User keeps .gpx files in a directory. Code reads latitude and longitude into a dataframe called "routes".
I use qmap to generate the map. I then use the aes command to plot the routes on tolp of the map.
Route line properties (e.g., color, size, type) can be changed.
