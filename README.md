# Surfs_Up
Module 9 - SQLite

## Overview of the Statiscal Analysis
For the analysis in this module I pulled out the temperatures for the month of June to compare with the temperatures for the month of December. I used SQLalchemy to query the SQLite data in hawaii.sqlite. I converted the results from that query into a list and then that list into a DataFrame.

## Results
I looked at the .describe() results from each DataFrame to compare the June temperatures against the December temperatures. 
* The mean temperature in June is nearly 4 degrees warmer than the mean temperature in December.
* The max temperature in June was only 2 degrees warmer than the max temperature in December.
* The minimum temperature in June was 8 degrees warmer than the minimum temperature in December.

## Summary
The temperatures in June verses December are not as different as expected. I added the precipitation column to the query and created a DataFrame directly from that query. The temperatures and the precipitation give a better picture of the weather. The increased rain and lower temperatures might mean a slower December for the shop, but since the temperature is much warmer than many parts of the United States the tourists may not notice the decline in weather.