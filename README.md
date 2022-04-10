# Surfs_Up

## Overview of the Analysis
The purpose of this analysis is to determine temperature trends on the island of Oahu for the months of June and December to better assertain if a surf and ice cream shop business is sustainable year-round. 

## Results 
Deliverable one and two use Python, Pandas functions and methods along with SQLAlchemy to:
1. Filter the date column in the Measurements table from the hawii.sqlite database provided by the client W.Avy.
2. Retrieve all the temperatures for the months of June and December and create DataFrames for respective months.
3. Use the Pandas DataFrame describe() method to return statistical summaries of the temperatures for June and December.

![June_Temps](https://github.com/adecoste2/surfs_up/blob/main/Images/June_Temps.png?raw=true)
* The average temperature for June is ~75 degrees fahreinheight with the maxiumum being 85 degrees fahreinheight. 

![December_Temps](https://github.com/adecoste2/surfs_up/blob/main/Images/December_Temps.png?raw=true)
* The average temperature for December is ~71 degrees fahreinheight with the maxiumum being 83 degrees fahreinheight. 

## Summary
To gain a better understanding of if the surf and ice cream shop business is sustainable year-round I thought it imperative to additionally create two additional queries that analyze the percipitation statistical summaries for the months of June and December. 

![June_Precp](https://github.com/adecoste2/surfs_up/blob/main/Images/June_Precp.png?raw=true)
* The average percipitation for June is 0.1~ inches with the maxiumum percipitation being 4.4~ inches.


![December_Precp](https://github.com/adecoste2/surfs_up/blob/main/Images/December_Precp.png?raw=true)
* The average percipitation for December is 0.2~ inches with the maxiumum percipitation being 6.4~ inches.

