# PyBer_Analysis

### Overview

The purpose of this challenge was to utilize our matplotlib skills to plot the ride data across different city types. We looked into the number of drivers and the fare rates among the different city types. In this analysis we figured out the total number of rides, total drivers and the total fare between all cities. With those values we were able to figure out the average fare per ride and the average fare per driver for each city type. We then took all this data and put it into a data frame. We then added in the date to this data frame and pulled all the data from 1-1-2019 to 4-28-2019 and looked at it by week. Once we pulled all the data by week, we were able to plot it on a line graph to see the trend in the fares by city over each month. 

### Results

First we found the total number of riders in each of the different city types shown below. This is showing that the urban city type has the most riders of the three city types. well exceeding the other two. 

<img width="422" alt="total_rides" src="https://user-images.githubusercontent.com/45208773/134450134-095f8587-a3eb-4d16-87ca-14443bbbda3b.PNG">

Next we found the total number of drivers in each city type. The number of drivers in the urban city type is also the leading of the three types. 

<img width="431" alt="totaldrivers" src="https://user-images.githubusercontent.com/45208773/134450238-48cfdc20-5cc6-41c1-b898-e29a38d39d7b.PNG">

Last we found the total fares from each city type. The total fare is following suit, with the urban city type having the highest total fares.

<img width="360" alt="totalfares" src="https://user-images.githubusercontent.com/45208773/134450308-30762680-1ce0-4b06-92a0-679c33742625.PNG">

With those three pieces of information we were able to find average fare per ride, driver and fare per each city type. Using the variables we made for each of the total drivers, total ride and total fares. I was able to do a simple equation to figure out the average fares, by dividing the total fare by the total drivers and dividing the total fares by the total rides. Interstingly, the average fare per driver and average fare per ride was the highest in the rural city type, even though the rural city type had the least amount of rides and drivers. 

<img width="358" alt="avgfareride" src="https://user-images.githubusercontent.com/45208773/134450765-4c3a0a5e-ecba-494b-8645-cb8fc75ae1b5.PNG">
<img width="383" alt="avgfaredriver" src="https://user-images.githubusercontent.com/45208773/134450808-ddbc34bd-9e42-4362-ac34-e4884b6d6a19.PNG">

### Summary
After all the analayzing, it makes sense that the urban city types would have the highest amounts of riders and drivers due to population being much higher in urban areas. My guess is that not as many people in the rural areas are in need of a ride, so when they do need a ride, there are less drivers available and the drivers are able to increase their fares. Whereas in an urban area, there are so many drivers, customers are going to go with the best rate. Another reason I believe the rural fares are much higher is because the distance is probably much longer in a rural area vs an urban area. Sometimes driving 1 mile in a city can take as long as driving 5 miles in a rural area, but if they are charging per mile than the that ride will always cost more. We could take a deeper look into the months and day times to see when rides are in hgihest demands in the riral areas, for instance weekends or holidays, and offer promo's so that the rates are not as high in the rural areas. Pyber could potentially offer incentives to suburban and urban drivers to venture out toward the rural areas to make more rides avilable at a lower rate. Pyber could also offer a "group ride" option to customers and drivers in the urban areas where there are a lot more riders to decrease the number of drivers and raise their average fare.
