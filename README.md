# New Orleans STR

Datasets:

* (2023-07-17) https://data.nola.gov/Housing-Land-Use-and-Blight/Map-of-Short-Term-Rental-Licenses/j5u3-2ueh

Yes this all came from one dataset, if you are here to complain that your privacy was violated please complain to the City of New Orleans.

I wrote this one afternoon to test folium and because there was a recent update to the STR data.  

Hopefully this will make it easier for people to track down the AirBnButtholes in their area!

https://s3.amazonaws.com/filestogeaux.garyscorner.net/pub/STRMap.html  <- map for now

s3://filestogeaux.garyscorner.net/pub/STRMap.html <-  This is where the map will live, its a requester pays bucket so you pay for the download (something like $0.09/gb).  Use the amazon cli with the switch "--request-payer requester"

Normally I avoid uploading things that turn out this simple and quick to write but this might actually be useful.

Chears,
Gary B
