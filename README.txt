DATA512 Final Project
Corey Christopherson
12-10-2019

The purpose of this project is to estimate aquifer health on Bainbridge Island, WA through an analysis of Department of Ecology well log data

Project information and data can be found in the Github repo https://github.com/chrico7/data-512-final-project

###
## Data ##
###

1. ed0c1eae-6b80-41dc-9424-0ccc1aa157c5_11052019.csv
   Located in the TextSearch_WellReports folder, this data is the raw well logs data from the WA Department of Ecology downloaded from the Text Search Utility

###
## API Documentation ##
###

1. NGS Coordinate Conversion and Transformation Tool (NCAT) API from the National Oceanic and Atmospheric Administration (NOAA)
   API that takes a coordinate from the State Plane Coordinate System and returns the correct latitude longitude
2. Open-Elevation API
   API that takes a latitude longitude value and returns the elevation at that location

###
## Final Data Fields ##
###

The final data fields for the study are contained in the well_data_bainbridge_island_final.csv file

| Well Log Id        | Unique well ID
| Well Comp Dt       | Well completion date
| Year               | Well completion year
| Well Depth Qt      | Depth of well in feet
| Well Diameter Qt   | Diameter of well in feet
| Well Depth         | Depth of well in feet as measured from mean sea level (MSL)
| elevation          | Elevation of well location from the Open-Elevation API in meters
| elevation (ft)     | Elevation of well location from the Open-Elevation API in feet
| St Plane Xcoord Nr | Well horizontal geographic coordinate value, WA State Plane Coordinate System
| St Plane Ycoord Nr | Well vertical geographic coordinate value, WA State Plane Coordinate System
| latitude           | Well latitude from the NGS Coordinate Conversion and Transformation Tool (NCAT) API
| longitude          | Well longitude from the NGS Coordinate Conversion and Transformation Tool (NCAT) API


