# PLACES - BUSINESS DATA

Extract business data using Google Places API.

https://developers.google.com/maps/documentation/places/web-service/search

Search string examples

* Retrieve an array of restaurants, gps locations, names and addresses
https://maps.googleapis.com/maps/api/place/textsearch/json?query=burgers+chelsea+manhattan+restaurant+new+york+city&type=restaurant&key=${APIKEY}

* Retrieves and array of restaurants based on zip code. A second query is executed for every business found to retrieve additional google places info, such as websites, operating hours and phone numbers
https://maps.googleapis.com/maps/api/place/textsearch/json?query=restaurant+78749&key=${APIKEY}

Other packages to explore

https://www.npmjs.com/package/use-places-autocomplete

https://www.npmjs.com/package/@react-google-maps/api

https://apify.com/drobnikj/crawler-google-places
