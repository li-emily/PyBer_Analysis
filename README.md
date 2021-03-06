# PyBer_Analysis

## Overview

### Purpose
> V. Isualize has given you and Omar a brand-new assignment. Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. Finally, you’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

This assignment had us practicing mostly with manipulation of DataFrames using Pandas. Originally, we practiced finding summary statistics, calculating percentages, creating bubble charts, box-and-whisker plots, and pie charts. For the challenge, there was merging of DataFrames together, using groupby to create a summaries, as well as cleaning and formatting. Additionally, we were creating pivot tables, using loc on pivot tables to then create a DataFrame, and resampling by week to create the last DataFrame. Finally, we used object-oriented interface plotting with Matplotlib's graph style 'fivethirtyeight' to create a multiple line graph.

### Resources
- Language: Python 3.7.10
- Interface: Jupyter Notebook
- Environment: Miniconda
- Packages: Numpy, Matplotlib, Pandas, SciPy

## Results

### PyBer Summary DataFrame
![PyBer Summary DataFrame](https://github.com/li-emily/PyBer_Analysis/blob/main/analysis/Summary_DataFrame.png)

Based on the above data, we can see how total rides, drivers, and fares break down across all city types. By adding average fare per ride and average fare per driver, we are able to more easily directly compare Rural, Suburban, and Urban cities against each other. We can see that total rides outnumber total drivers in both Rural and Suburban cities, while total rides outnumbers total drivers in Urban cities. As a result, despite total fares being much higher for Urban cities, the average fare per driver is much lower. Average fare per ride is also lower in Urban cities. Rural cities have the highest average fare per ride and average fare per driver.

### Weekly Fare by City Type
![Weekly Fare by City Type](https://github.com/li-emily/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

This graph provides an easy visualization that total PyBer fares earned go in order by Urban, then Suburban, and finally Rural cities. There is a slight overall spike across the board in the last week of February 2020. 
- Urban cities had mild fluctuations, with spikes up and down mostly around the month of March, with modest growth. Urban cities started at around $1,700 per week in January and grew to roughly $2,250 by the end of April.
- Suburban cities mostly had that slight increase in the last week of February, also with modest growth from around $750 to $1,400.
- Rural cities had an overall more jagged weekly fare throughout time, but mostly remained below $500, roughly starting and finishing at the $200 mark. 

## Summary
Based on the results, these are three business recommendations to the CEO for addressing any disparities among the city types.
- Because of the overall spike in all rides across city types in late February, there should be some information gathering on why this occurred. Was this due to a promotion on PyBer's part, or an outside influence like a popular movie that motivates more people to go out? PyBer should also check overall fluctuations by city type to see what is powering them, because figuring out the reason behind these sudden spikes and slumps will help the company make more accurate future decisions. 
- PyBer should also do more analysis in regards to local gas prices in these cities. This is mainly due to Rural city rides, which are expected to be longer and thus have higher fares, but the drivers themselves are potentially also spending more. Additionally, gas is potentially also more expensive for Rural cities. Collecting local gas prices would help PyBer calculate costs that drivers would need in order to turn a profit, and decide which direction PyBer itself needs to go towards to raise revenue.
- A potentially concerning issue is that there are more drivers than rides in Urban cities. Based on the data, this means that there is at least 780 drivers who are not getting any passenger rides, and presumably, not earning any money. PyBer must figure out how to fix this disparity, which could be by advertising PyBer rides more to help attract more customers, or encouraging higher standards for drivers to eliminate this overabundance.
