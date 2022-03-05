# PyBer_Analysis
Module 5 Challenge
## Overview of Project
The objective of this project was to analyze ride-sharing data from different cities and types of cities over a period of time.  The module 
uses pandas dataframes to summarize data, Scipy for statisical information,  Numpy for scientific computing to generate data to used to 
display results on charts using matplotlib.  

Merging two dataframes (City data and Rider data) was essential to provide a way to calculate ridership, driver count, total fares collected by 
city and city type.  Information such as average fare by city type and average fare by driver could be calculated using this combined dataframe.
We also used the group by function to be able to get totals by city and city type.

We also formatted columns within a dataframe so that the numbers presented were much more readable.

Pie charts showed us percentage fares and total rides and total drivers  by city type.   Each of these charts could also be formatted
with a title, coloring for different slices, labels for each section of the pie.

Box and Whisker plots showed us statiscally (mean, median, mode) how ridership compares to each city type.

![Box and Whisker Fares by City Type](https://github.com/gaudiom4git/PyBer_Analysis/blob/main/analysis/Fig2.png)

## Results

Based on the pie charts from the module lessons, we can see that the Urban type collected the most in fares (62.7%), while suburban came in second at 30.5% and Rural at 6.8%.
Ride count and driver count pie chart had similar results percentage wise.

![Fares by City Type](https://github.com/gaudiom4git/PyBer_Analysis/blob/main/analysis/Fig5.png)

Even the line chart in the challenge, we can see that Urban had the highest fare across Spring 2019 (Jan thru April) with Suburban in second and Rural in third.  
Lowest fare collected occurs in January where the peak in the last part of February for all 3, but Suburban also has a high peack end of April. 

![Fares by City Type](https://github.com/gaudiom4git/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

## Summary

Recommendations to the CEO for each of the 3 city types would be:

(1) Suburban ridership peaks in April where the other two drop a bit.  If possible, maybe shift some drivers or higher more in that timeframe to see if
more riders can be picked up if there are more drivers.

(2) Rural ridership jumps up in April, so maybe add more drivers there in that timeframe to gain more riders.

(3) Suburban swings up and down throughout the 4 months.  Suggest that more investigation as to why there are sunch large shifts in ridership across those 4
months to see what can be done to improve business.