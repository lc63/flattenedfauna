# Cleaning Log

### Dataset: USARoadkillDataGarneau_2012-2015.csv
#### Original Download: http://epicollectserver.appspot.com/project.html?name=RoadkillGarneau



Removed observations with no latitude or longitude

Left observations with no species name because there are associated pictures that can be used for identification

Replaced empty Date cells with value in corresponding 'Date Created' column

Replaced all empty cells of String format with 'Null'

Replaced all empty cells of Numeric format with '-9999'

Changed Data format to YYYY-MM-DD

Converted all values in 'Temperature' variable to Fahrenheit

Removed Sting characters in 'Temperature' variable

Escaped all special characters