# PyBer_Analysis
## Overview of the analysis
The purpose of this analysis is to summarize ride-sharing data by rural, suburban, and urban city types and to outline how the different city types  We'll reflect the frequency of rides and their respective fare costs. We'll use Pandas and Matplotlib to plot the total fares for each city type and we'll then be able to see the differences, or similarities, in the number of total fares within any given month.

## Results
First, we've captured the total rides, total drivers, total fares, and averages for fares per ride, and fares per driver, for each city type:

**Total Rides:**

![image](https://user-images.githubusercontent.com/89496798/141698342-4f0e0dc0-aea0-43b8-b6d1-58ed93541aed.png)

**Total Drivers:**

![image](https://user-images.githubusercontent.com/89496798/141698366-65d508a9-960e-4135-966c-22ed9f8ccbc0.png)

**Total Fares:**

![image](https://user-images.githubusercontent.com/89496798/141698377-7b1daa90-b9fc-4247-a705-4f40bbb5484b.png)

**Average Fare Per Ride:**

![image](https://user-images.githubusercontent.com/89496798/141698388-85c059d4-efa1-42d6-9967-882e33b73bf5.png)

**Average Fare Per Driver:**

![image](https://user-images.githubusercontent.com/89496798/141698395-3d5b5029-5e35-4383-85ba-3e440d9a26b2.png)

By creating a dataframe to include all the data listed above, we can further analyze:

![image](https://user-images.githubusercontent.com/89496798/141698410-9ddf6e06-cc1f-407e-8373-5741c5230762.png)

As we can see from the data above, it's evident that urban areas have a higher number of total rides. As expected, with such a high number of total rides, the number of total drivers and total fares is also significantly higher than those in rural or suburban areas. Also, it seems as though the number of rides has a direct impact on the average fare per ride and average fare per driver. Rural areas show the highest average fare per ride or driver given the low ride count and frequency. On the other end, urban areas have averaged to have the lowest fares per ride and per driver.

Below, we can visualize the data throughout the months of January to the end of April:
![image](https://user-images.githubusercontent.com/89496798/141698687-a84316d4-190b-45d8-955f-2ad4ec5dfbb8.png)

## Summary
It's expected that urban areas consist of a higher volume of usage. The density of population in urban areas require a strong need for immediate transportation offered by PyBer and this is what we're seeing after tracking the total fares by city type. One pattern we do see is the consistency of rides for all city types as the months of the year progress. For example, the number of rides at the end of February slightly peaks for all city types. This may be due to a change in weather or a local event. Regardless, it's important to provide more accessibility for those in suburban, and especially in rural, areas than those in urban areas. Those in rural areas may be less inclined to use PyBer given the high average cost per ride. PyBer may be able to decrease the average fare per ride by increasing the number of drivers in rural or suburban areas. It may also make sense to incentivize more urban drivers to travel to rural or suburban areas. This may tighten the ride count disparity among all three areas by redistributing the range of service. Another option could be to include a carpool option for those in rural and suburban areas in an effort to split the high fare price. This would be a huge advantage for those living in suburban areas who may be traveling to and from urban areas for work.
