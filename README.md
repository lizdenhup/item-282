# item-282 (wip)

It's that time of year again. The UofC is having its annual scavenger hunt and this is my small contribution.

\#snitchcock \#emphaticallyyes \#alburquerqueintlbaloonfestival

For item 282, the judges have requested "the most average census tract in America. We want to see the GEOID, a description of your rigorous yet creatively innovative methodology, and an illustrative map"

## Methodology

1. Understand the problem

As is the case with most scav items, I had no idea what this meant upon the first several readings. So I asked friends, and then emailed the customer service branch of the United State Census Bureau. Apparently, the US Census Bureau employs individuals who are both lovely _and_ helpful. You can find their response in the file entitled "response-from-census.md".

2. Follow the instructions provided to me by the US Census Bureau.

I downloaded the National Census Tracts Gazetteer Files	for the year 2018. These are based on the 2010 census. This is a .txt file containing the following fields:

USPS GEOID ALAND AWATER ALAND_SQMI AWATER_SQMI INTPTLAT INTPTLONG

I opened this file in Google sheets. You can find the spreadsheet [here](https://docs.google.com/spreadsheets/d/13V_61OSEUaBGR1c70YHgCn3a-s5ZuGZGa4xDTScvaUQ/edit?usp=sharing).

I averaged the floating point values for columns for which this made sense using regular ol' Google formulas, i.e. `=AVERAGE(F3:F)` etc. You can see the averages in the top row of the spreadsheet.

### Results
