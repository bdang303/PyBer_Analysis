# Pyber Analysis using Matplotlib & Pandas

## Overview of the Pyber ride sharing analysis:
Using data from a hypothetical ride sharing company “Pyber”, this analysis consisted of gathering data elements from CSV files and applying methods in Pandas & Matplotlib. Data from the CSV files contained details such as number of rides, drivers, fares, within various cities at specific date & time stamps. The python script enabled this data to be interpreted and summarized to understand relationships between these data elements and eventually inform how to create a more efficient experience for both drivers & riders.  

## Analysis Results

### Ride Summary by City

The data on rides were group into 3 primary city types: Rural, Suburban, Urban. 

![Ride Summary by City Type](https://github.com/bdang303/PyBer_Analysis/blob/main/Resources/Pyber_fare_table.png)

* The Rural areas had the least number of rides (128) & drivers (78), which resulted in lowest total fares ($4,327), highest average fare price ($34.62 per ride) & highest average fare price per driver ($55.49).
* The Suburban areas had over five times the number of rides (625) and drivers (490) compared to Rural areas, and had a slightly less average fare price ($30.97) and average fare price per driver ($39.50) with total fares of $19,356.
* The Urban areas not surprisingly had the highest number of rides (1625) and drivers (2,405), 13 times that number of rides in the Rural areas. Due to the higher number of rides & drivers, the average fare price was significantly cheaper than the other two areas ($24.52 per ride; $16.57 per drive) and total fares of $39,854. 

### Fares in January through April

![Fares Line Graph](https://github.com/bdang303/PyBer_Analysis/blob/main/Resources/PyBer_fare_summary.png)

•	The 3 areas seems to experience peaks and valleys around the same time


## Analysis Summary
Based on the results, below are three recommendations that would enhance Pyber’s model: 

•	Increase presence & number of drives in the Rural areas, as maybe the average fare price may be slightly higher than what riders would expect. 
•	Reallocate number of drivers in Urban areas and incentivize them to take rides in Suburban or Rural areas as there is an abundance of drivers in Urban cities.
•	Continue to focus on having enough supply of drivers in Urban areas as that is where there is the highest demand of rides and generates the highest total fares.
![image](https://user-images.githubusercontent.com/93288351/152630199-797b5de9-75c9-418a-9940-6fff1f2d8cba.png)
