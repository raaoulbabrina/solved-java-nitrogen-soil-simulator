Download Link: https://assignmentchef.com/product/solved-java-nitrogen-soil-simulator
<br>
Objective of lab is to create a java nitrogen soil simulator

Supplied map: https://ufile.io/59rmx

You will use the supplied map which represents the average elevation of each 100 by 100 metre cell. You will start off with a constant amount of nitrogen in each cell and calculate the remaining nitrogen in each cell every month for 100 years. Nitrogen leaves each cell as it washes away in direct proportion of the difference in elevation between the cell and its neighbours. Each metre of difference causes 0.001 percent of the nitrogen per mm of rain to wash into the adjoining cells of lower elevation.

Each cell starts with 500 kg of biological nitrogen and receives 16 kg of new nitrogen per metre of rainfall every year. I want you vary the rainfall every month of every year a little, but stay within 10 percent of the averages above. After you open your elevation map I want you to save it as a .txt (Tab Delimited) file from Open Office and load it into your Java program. Perform the 100 year simulation in your program and write out a 10 by 30 grid of remaining nitrogen values as a .csv (Comma Separated Value) file. Load that back into Open Office and colour the cells based on the following algorithm. The third of the cells with the most nitrogen colour dark gray, the middle third light gray, and the lowest third white. I want a printout for every 25 (that makes for 5 maps) years showing what (if any) changes happen.

The rain data in mm is presented as follows January 94.3, February 71.7, March 46.5, April 28.5, June 20.7, July 14.9, August 19.6, September 27.3, October 51.2, November 98.0, December 108.9.