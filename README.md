# PyBer Analysis

## Overview
PyBer is a Python-based ride-sharing App Company that wants to understand how to better serve in regards to affordabilty and coverage. For that, they hired a data analyst to process their data and create charts to show the relationship between the city and the number of riders and drivers, the percentage of total fares, riders and drivers by type of city (Urban, Suburban and Rural).

## Results

The following three pie charts show clearly that the Urban city holds the most fares, drivers and rides. And even the breakdown is similar in all three cases: between 60 and 80% of all fares, rides and drivers are concentrated in urban areas. Suburban areas are responsible for percentages between 16 and 30% and, lastly, rural areas have a slim slice varying from 2.5 to 6.8%. These numbers are not surprising since it is logical to have more drivers and rides in more populated areas, which usually means more demand.

![Fig5](/analysis/Fig5.png) ![Fig6](/analysis/Fig6.png) ![Fig7](/analysis/Fig7.png)

When we correlate these charts with the following one (PyBer Ride-Sharing Data), we notice that average fare decreases as the number of drivers increase: it seems that, the more drivers, the more riders, the less the ride will cost. That also makes some sense according to simple supply and demand concepts. 

![Fig1](/analysis/Fig1.png)

Lastly, the following chart shows the revenue from January to March 2019 aggregated in a weekly basis. The result shows fairly smooth lines, not big variations over time and the three lines can be easily related to the percentages the pie charts shown revealved above.

![PyBer_fare_summary](/analysis/PyBer_fare_summary.png)

## Summary

!(/analysis/PyBer_summary.png)

 According to the data, the urban areas are responsible for the majority of the revenue, but my recommendation is to dive in a deeper analysis taking into account:
    * the population size of each area: it would be interesting to find out the correlation between rides and the population of each area. Would they be all similar in percentages? Or would they vary? The reason for my recommendation is because we compared urban, suburban and rural areas, but the real number of people in each area was never disclosed. The number of rides may be lower simply because there are less people!
    * the wealthiness of each area: another amazing information would be to find out how wealthy each area is. We might think that person who is unemployed, for instance, will not spend his money with this kind of service or, if he did, it would be just for essential commutes.
    * the ride length: lastly, the ride length might give us a final take because all we had was how much each ride cost, but that absolute value does not show much. It could be a short ride that cost a lot or the other way around making profit remarkably distinct. That being said, 