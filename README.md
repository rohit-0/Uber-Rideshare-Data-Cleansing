# Uber-Rideshare-Data-Cleansing

Libraries used: 
* pandas (for analysing the data)
* datetime (for handling date and time data)
* networkx (for using dijkstras algorithm to find shortest paths)
* matplotlib (for plotting the data for EDA)
* folium (plotting coordinates on interactive maps)
* KNeighborsClassifier (for clustering)
* LinearRegression (To perform linear regression)
* seaborn (To plot scatterplots and residualplots)


## 1. Introduction
The dataset provided contains data of Uber Rides.

The description of the data is as follows:
* id - Unique ID for the journey
* Uber Type - Whether the ride was Uberpool,X or Black
* Origin Region - Region from where journey started
* Destination Region - Region where journey ended
* Origin, Destination Latitudes and Longitudes - Geograpical coordinates of start point and end point of the journeys
* Journey Distance - Distance from start point to end point of journey.
* Departure Date, Time - Time and date of commencement of journey.
* Travel Time - Time duration taken to reach the destination.
* Arrival Time - Time of arrival to destination.
* Fare - Fare of the journey

This program performs various Graphical and non Graphical EDA to observe and fix errors in the dataset.

There are 3 datasets namely:
* Dirty Data : 
Dirty data has errors which have to be fixed using various Graphical and non Graphical EDA.
* Missing Data : 
Missing data has missing values which need to be imputed using other information provided.
* Outliers : 
Outliers data contains outliers which have to be identified and removed.
