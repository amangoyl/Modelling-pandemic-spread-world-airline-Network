# Modelling-pandemic-spread-world-airline-Network
A detailed analysis of spread of pandemic using World Airline Network with Node Removal Analysis.

Python Libraries used:

NetworkX

EoN (Epidemics on Networks)

## Node Removal Analysis- Objective
Major significance on node removal analysis is to detect most influential nodes (airports) in the network which can be removed (locked down) to stop the spread of pandemic effectively. The analysis shows that removing the most Bridging Central nodes and the most eigen vector central nodes can curb the epidemic spread at an early stage. 

## Dataset
The dataset used are two interdependent sets of data available at openflights.com - Airline Routes dataset and Airports dataset. The Airports dataset contains a list of 3321 airports across the globe, along with their airport codes, latitudes and longitudes. The Airline Routes captures 67663 routes between 3321 airports on 548 airlines all over the world. The following figure depicts the final network created by using these datasets, which is a geolocational overview of the data. The colouring is just for visualization purposes with no other relevant significance. (Created using Gephi)


![image](https://user-images.githubusercontent.com/102705658/230988003-be04beb5-e665-49fe-80e3-5d61622ac285.png)


Following image provides a broader picture on time taken by each country to get infected by aggregating airports in each country. The lighter the country is in the map, faster it got infected

![image](https://user-images.githubusercontent.com/102705658/230990494-3d436af8-5c47-4790-9d4b-c20f35ef66f8.png)



