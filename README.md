# DA_GA_FAP

## Using-Genetic-Algorithm-for-Dynamic-Allocation-of-Facility-Location.

The aim of this project was to use the given data set to derive solution to the problem of dynamic facility allocation, the facilities in this case are the rescue hubs like fire station and small dispencary/hospitals.

Focus was to cater to the need of an emergency situation keeping various factors in mind, such as travel time and probable number of emergency cases during a particular time of the day.

In order to achieve this we first try to predict a set of potential points that will require rescue then we tried to get potential rescue station, in the vicinity of these points with the contraint being that any one rescue point is catered by any one hub during the time of rescue and that one hub caters only to that one rescue point at that time. 

## Intro to the data 

Refer - [a link](https://github.com/beginner46/DA_GA_FAP/blob/main/data.zip)

Contains information about the rescue vehicles requirements (fire trucks, ambulances, rescue tanks and water tanks) of
various points across three different time intervals of the day.

Contains information regarding various points that can be a potential location. Along with the compactness and
population density information of various travel routes to them.

The data also contains various shape files that can be used to get an idea of how the points are distributed over a map.

## Pre processing the data

Refer - [a link](https://github.com/beginner46/DA_GA_FAP/blob/main/Info_data_pre_processing%20.txt)

Performed cleaning of the data, normalized it for computational efficiency and fixed the dimensionality mismatch (previously the data had issues like non-zero travel time between a point and in itself)

For the codes of Data Pre-processing refer - [a link](https://github.com/beginner46/DA_GA_FAP/blob/main/Data%20Pre%20Processing.zip)

