# Parking-Lot-Area
This is the first iteration of ongoing research to develop metrics for car centrism. this code allows you to calculate the total area of parking within practically every US city.
Data is from OpenStreetMap, which contains coordinate information for the vertices of all recorded amenitys labeled "parking". using these vertices, we can compute the area of each individual polygon, and find the total area of parking in a give city. 
City boundaries are designated by OpenStreetMap (administrative level 8 boundaries), and does not reflect total MSA (Metro Statistical Area). 
Future Improvemnts: Impliment MSA boundaries using GIS data, as well as downtown area boundaries. Improve EPSG projection computation.
