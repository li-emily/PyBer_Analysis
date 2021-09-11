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

### Weekly Fare by City Type
- Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.

# Summary
Based on the results, these are three business recommendations to the CEO for addressing any disparities among the city types.
- Check to see what happened in late February, slight overall spike, and in April, why was there a sudden spike downwards for Urban and Suburban
- Do more analysis in regards to each city types' length of ride, how fare is calculated
- There are more drivers than rides in Urban cities. This means that there is at least 780 drivers who are not getting any passenger rides, and presumably, not earning any money. Must figure out how to fix this disparity, whether by advertising PyBer rides more to help attract more customers, or encouraging higher standards for drivers to eliminate this overabundance.
