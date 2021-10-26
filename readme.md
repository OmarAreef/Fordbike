

> # Exploring trip data of Ford go bike 
## by (Omar Aref)

## Preliminary Wrangling

> Data set consists of 180K+ records with 22 columns represnting the duration , data , station , gender and customer type.


## Summary of Findings

> Here I found that the further the start station is from the center it has higher average trip duration, Customers have higher average trip durations vs Subscribers , males represent the majority of the data set , the average trip duration falls between 6 - 11 minutes , Stations are located in 3 Clusters , Weekends have a lower count of trips compared to weekdays.


## Key Insights for Presentation

> Our key variable under study is the Duration of the trips.After investigating it by itself, I found that the average trip duration of trips is between 6-11 minutes and there are some outliers that have trip times in the 100 of minutes.
>Then we started the bivariate analysis on duration against (Gender , user types , day of the week , birth year) 
	1)against Gender:
		Nothing of real importance was found since the differnece was less than a minute between males and females.
	2)against User types:
		Here Customer users had higher trip durations than subscribers.
	3)against day of the week:
		 Weekends have a higher mean and interquartile range than weekdays.
	4)against Birth year:
		nothing of real significance was found all users have the same average of trip durations.
We will then plot the the locations of the stations using the longitude and latitude variables which we will use next.

>We added the Duration of the trips to our map of locations to see the relation between them.The plot that was created showed the further away a point is from the other points or the center (i.e outskirt point in the cluster not the whole region) the longer the trip duration it is starting from it.