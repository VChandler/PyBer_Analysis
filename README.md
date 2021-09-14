# PyBer Analysis
## Overview  
V. Isualize has requested an analysis of the ride-sharing data by city type for the purpose of generating business recommendations.  The timeframe specifically focused on data from 1/1/2019 through 4/28/2019. Python was used to join and re-shape data in order to visualize the aggregate data points (such as number of drivers, avg fare per ride, total fare, etc.) for rural, suburban, and urban city types. 

## Results  
From January 1, 2019 through April 28, 2019, a number of data points were gathered and summarized by city type:
![final-type-summary](https://user-images.githubusercontent.com/88070999/133192916-17a467b8-8a8d-4772-808c-fb68370f2886.png)  

A few points of interest:
* Rural cities had far fewer rides during the timeframe compared to suburban (which was 5 times higher) and urban (13 times higher), and yet generated substantially more in average fare per driver: $55.49 compared to $39.50 (Suburban) and $16.57 (Urban).
* Rural cities also had the highest average fare per ride, which was $3.65 more than suburban cities and $10.09 more than urban.
* Urban city types, as expected, had 2,405 total drivers.  However, this turned out to be a staggering 31 times more drivers than rural city types.
* Despite have lower average fares per ride and fares per driver, the sheer number of drivers in urban cities resulted in 63% of the total fares generated during the timeframe among all the city types.  Graphed over time:

![final-graph](https://user-images.githubusercontent.com/88070999/133193993-3a3238a4-c783-49bb-b1d5-501a160ab966.png)

## Summary  
To address the wide disparities between the three city types, there are a few recommendations for consideration:
1. Rural cities generate the highest fares per ride and fares per driver. PyBer may consider a campaign to attract additional drivers in order to improve profitability in these city types that are often more geographically dispersed than suburban or urban settings.
2. On the flip side, advertising for more riders in rural cities may improve the number of rides, thus improving the total fares for the company.
3. Urban drivers may be incentivized to work in nearby suburban cities.  This would increase the number of drivers (albeit more sporadically) in suburban cities, ideally generating more than 2x the average fare for drivers and $6 more in average fare per ride.
4. All three city types saw a spike in total fare towards the last half of February.  Further analysis of the underlying causes may reveal some learnings that could be applied broadly to all city types.
