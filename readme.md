# Complete jQuery Store Locator with Google Maps API, Google Distance Matrix API, HTML5 GeoLocation & Google Maps KML file as data source

##Features:
  * Fully client-side application with XML file data source. No server-side scripting or database required.
  * This is a jQuery plugin; hence jQuery reference is required in order for it to work :) It also requires a Google Maps JavaScript API v3 reference for the mapping stuff
  * Takes in a Google Maps KML file as a source of store locations [developers.google.com/kml/documentation/mapsSupport](https://developers.google.com/kml/documentation/mapsSupport)
  * Uses HTML5 GeoLocation [](http://dev.w3.org/geo/api/spec-source.html) to determine user's location when applicable
  * Uses Google Geocoding API [developers.google.com/maps/documentation/geocoding](https://developers.google.com/maps/documentation/geocoding/) to work out user's location from supplied address details
  * Uses Google Distance Matrix Service to work out the driving distances to store locations
  * Uses jQuery.Deferred() object [api.jquery.com/category/deferred-object](http://api.jquery.com/category/deferred-object/) to work around the Google Distance Matrix Service's limitation of 25 destinations in one service call, thus making it multiple service calls asynchronously when required
  * Shows user's location on the map (0 marker)
  * Works out and displays nearest N (configurable variable) shops with their details in the list, showing the <name>, <description> from the data source file, driving distance in miles and a link to Google Map with driving directions
  * Shows nearest store locations on the maps with A-Z marker pins
  * Automatically chooses appropriate Map Zoom level to fit all locations on the map

##DEMO SITE: [optimax.apphb.com/demo.html](http://optimax.apphb.com/demo.html)

Inspired by original jQuery Store Locator plugin by Bjorn Holine [bjornblog.com/web/jquery-store-locator-plugin](http://www.bjornblog.com/web/jquery-store-locator-plugin); this is a github fork of his repo located here: github.com/bjorn2404/jQuery-Store-Locator-Plugin
