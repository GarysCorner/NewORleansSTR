# New Orleans STR

Datasets:

* (2023-07-17) https://data.nola.gov/Housing-Land-Use-and-Blight/Map-of-Short-Term-Rental-Licenses/j5u3-2ueh

[Open Map](https://s3.amazonaws.com/filestogeaux.garyscorner.net/pub/STRMap.html)  ( > 140mb long load times )

![Screen Shot](https://github.com/GarysCorner/NewORleansSTR/blob/master/ScreenShot.jpg?raw=true)

I wrote this one afternoon to test folium and because there was a recent update to the STR data.  

Hopefully this will make it easier for people to track down the AirBnB contact info.

https://s3.amazonaws.com/filestogeaux.garyscorner.net/pub/STRMap.html  <- map location for now

s3://requesterpays.garyscorner.net/datasets/html/STRMap.html <-  This is where the map will live, its a requester pays bucket so you pay for the download (something like $0.09/gb).  Use the amazon cli with the switch "--request-payer requester"

Normally I avoid uploading things that turn out this simple and quick to write but this might actually be useful.

Chears,

**Gary B**
