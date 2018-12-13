# RIOT

RIOT, the Road Information Object Transform, is a package that consists of road information as a function of USA road, a methodology to determine the road corresponding to a given longitude/latitude position, a mapping algorithm that maps location data to driver data, and a risk model to quantify a given road's auto-accident risk (independent of any given driver).

The road network and basic information objects, such as road type and road speed limit, are obtained from the open source road database, OpenSteetMaps via OSMnx. OSMnx is a python package for downloading boundary shapes and road networks from OpenStreetMaps.

Documentation for OSMnx, can be found here:<br/>
  
  Academic paper: file:///Users/samtaimourzadeh/Downloads/boeing-osmnx-street-networks.pdf<br/>
  Docs: https://osmnx.readthedocs.io/en/stable/osmnx.html<br/>
  Github: https://github.com/gboeing/osmnx<br/>
  
And OpenStreetMap Highway Key vaules are here:<br/>
https://wiki.openstreetmap.org/wiki/Key:highway<br/>
  
In addition to road objects provided by OSMnx, RIOT includes typical road traffic, accident density, and weather conditions as a function of location and time. 
