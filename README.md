# gears
script for generating involute gear template in svg

default mode at this point works off of diametral pitch.  TODO to work with metric module parameter
scale can be used to convert to other units.  25.4 for example will output the svg with 1px=1mm.

Most web browsers will only display the svg in positive quadrant, so offset can be used to shift.  
If importing to a CAD package then it may be best to set offset to zero (your preference)
