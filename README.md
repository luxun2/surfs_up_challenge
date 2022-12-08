# Surfs Up



## Overview of Project
###### Explain the purpose of this analysis

Here we focused on using sqlalchemy to interact with sqlite databases. We analyze temperate and precipiation data on the premise that we wnat to open up a Surf and Shake shop serving surfboards and ice cream to locals, and tourists. We filter data gathered from stations around the months of December and June to present to investors so we can open the shop.


## Results
###### Using images and examples of your code.

Statistics about the dataframes we made for the months of June and December can be viewed below. 
Three key differences can be observed between the months. 
* December has lower mean temps.
* December has lower lows in temps than June similar highs. 
* December has much higher standard deviation or variation in temps.

![This is an image](https://i.imgur.com/5FVbkKG.png)
![This is an image](https://i.imgur.com/da0C8uL.png)

## Summary: Provide a high-level summary of the results and two additional queries that you would perform to gather more weather data for June and December.

Well as we can observe there is definitely a viability to run a shop year round just based on the temps we got for these two months. However it would be good to look at the stats for every single month and plot them in matplotlib to get even more information. It would also be useful to get similar stats for precipiation here as well. Another additional query that would be nice is to get data regarding wave height or tide charts to view the best months to be surfing. 
