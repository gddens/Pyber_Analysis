# Pyber Analysis
## Overview
The purpose of this new analysis was to both summarize a variety of metrics (Total Rides, Total Drivers, Average Fare/Ride, and Average Fare/Driver) for each of the three city types (Urban, Suburban, and Rural), as well as create a line plot showing the total fares for each city type over a period of three months (January - April) in order to determine how Pyber performed in each type so that the company can make informed business decisions based off of this data.

## Results

A summary dataframe was created to display the metrics mentioned above in the Overview:

![image](https://user-images.githubusercontent.com/86032451/127710466-deb1f22d-47ea-4912-9931-3292f891d752.png)

A line chart was also created to display just the Total Fares over a period of four months:

![image](https://user-images.githubusercontent.com/86032451/127710538-b31662c6-ccfb-4450-8962-c3f906598bb1.png)

Below is a breakdown of what can be gleaned from this data by each metric.

### Total Rides

* Urban had the highest total for rides (1625) - exactly a thousand more than Suburban, the next highest (625) - with Rural having the lowest number of rides (125).

### Total Drivers

* Urban had a higher total for drivers by a longshot over suburban (2405 and 490 respectively) with Rural having the lowest total (78).

### Total Fares

* Following the pattern established above, Urban had the highest total fares ($39,854.38), followed by Suburban ($19,356.33), then Rural ($4,327.93).

### Average Fare per Ride

* In a reverse of the pattern, Rural has the highest Average Fare per Ride ($34.62), followed by Suburban ($30.97), then Urban ($24.53). This is because even though the total fares for Rural was significantly smaller than Urban, so was its Total Rides metric, which meant that there was a smaller base over which to spread the Total Fares. 

### Average Fare per Driver
* Same as above, Rural has the highest Average Fare per Ride ($55.49), followed by Suburban ($39.50), then Urban ($16.57), for the same reason mentioned above. 

## Summary
In summary, Rural appears to be the least profitable city type based on metrics listed above, followed by Suburban, then Urban. The company could therefore boost marketing in Rural and Suburban areas to increase awareness of the company and potentially gain more riders that way. They could also hire more drivers in Rural and Suburban areas since lack of rides could be due to lack of available drivers. A third recommendation, however, could be to decrease fares in Rural and Suburban areas, given that they had the highest Average Fare per Ride (and per Driver), and these higher fares could be keeping customers away.
