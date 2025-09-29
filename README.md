# GEOG4910_trailcalculator
## Purpose:
This tool calculates the difficulty along a hiking trail based on the slope of the trail. It helps hikers know when the terrain gets steeper along the trail

## Data:
The data that needs to be supplied is a shapefile of the trail you want to calculate the difficulty of and 10m Elevation DEM data in the area that the trail is in

## Output:
This tool will create start and end points every segment length (in this case, every 1 mile) to separate the trail into different sections. In the attribute table of the trail shapefile, there will be a column that describes the difficulty level of the segment of trail that the user is interested in. It can be easy (2% slope or less), moderate (8% slope or less) or hard (above 8%).
