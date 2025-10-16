# Seattle and Honolulu Rain Precipitation Report. Does Honolulu get more rain than Seattle?

## Introduction
This report compares daily rain precipitation between Seattle, Washington and Honolulu, Hawaii from 2018 to 2022. There is perception that tropical locations like Honolulu, which is often perceived to have light rain almost every day and occasional sporadic heavy rainfalls significantly longer and stronger than Seattle. Does this perception hold true? 

It analyzes five years of daily precipitation data to answer this question by examining:
- Daily precipitation patterns and totals
- Average precipitation differences 
- Seasonal variations and trends
- Heaviest rain months identification and year-to-year comparison across 2018-2022

The goal is to determine definitively which city receives more rain and understand the patterns behind the differences.

## Rain Precipitation Analysis (2018-2022)

This comprehensive analysis examines precipitation patterns between Seattle and Honolulu through multiple analytical approaches, progressing from cumulative average comparisons, seasonal distributions, and year-to-year variations during the heaviest precipitation periods.

### Average Daily Rain Precipitation
Examine cumulative average daily rain precipitation for Seattle and Honolulu from 2018 to 2022 to understand overall differences in precipitation levels.
![daily_mean_precipitation](img/average_precipitation.png)

These chart shows that Seattle on average and in conclusion in total receives almost 3 times the amount of rain precipitation during the 5 year period in comparison to Honolulu.


### Daily Rain Precipitation Distribution and Seasonal Trends
While Seattle has higher average daily precipitation, it's important to analyze daily patterns to understand seasonal variations and extremes.

![Daily_Rain_Preciption](img/daily_precipitation.png)

The data shows that light rain occuring daily in Honlulu is not visible in the chart. The ocassional spikes on the chart are tropical storm events which are rare. Seattle clearly show more frequent noticeable rain events. Both cities show seasonal trends with most rainy days in the winter months (November-February) and lower in the summer months (June-August). However, Seattle's winter months have significantly higher daily precipitation levels on most of the days compared to Honolulu.  

### Seasonal Analysis and Monthly Variations
Distributing the daily data by month to observe monthly trends.

[monthly_distribution_precipitation](img/monthly_precipitation_zoomed.png)
*The x-axis is reduced to 0-1 inch to better visualize data*

Seattle shows heavy monthly rain from late fall through early spring (November-March) and a dry summer. Honolulu's rainfall is more evenly distributed throughout the year, with highest rain in winter months. We can also observer that for nearly every month, Seattle's median rainfall values exceed Honolulu's.

## Year-to-Year Analysis of Heaviest Rain Months (November-February)

Focusing on the heaviest rain months (November to February) to compare year-to-year variations between Seattle and Honolulu.

![nov_feb_precipitation_by_year](img/monthly_precipitation_years_cmp.png)

Graph shows that there is no significant difference in the monthly variation across years for Seattle, and variations exist are mostly within the month. For Honolulu we see more variation between years than in Seattle. While rain precipitation is generally lower during these months, with one major exception: December 2021 saw unusually heavy rainfall, making it the only month in this five-year peak-season comparison where Honolulu's average daily precipitation surpassed Seattle's.

## Conclusion
Based on the analysis of daily rain precipitation data from 2018 to 2022, Seattle consistently receives more rain than Honolulu. The average daily precipitation in Seattle is higher than that of Honolulu, and the total precipitation over the five-year period also indicates that Seattle experiences significantly more rainfall. We can conclude that it rains more in Seattle than in Honolulu. Similarly, monthly analysis shows that Seattle has higher average daily precipitation for every month of the year compared to Honolulu. Seasonal trends are evident in Seattle with higher precipitation in the winter months. 


## Data Sources, Collection, and Preparation

### Data Sources
The data used in this report is sourced from the NOAA website: 
 https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND.
*Note: Honolulu data is from Honolulu Airport station USW00022521 and Seattle data is from station GHCND:US1WAKG0225.*

**Data discrepancy**
- Honolulu - no missing precipitation values.
- Seattle - missed precipitation readings for 190 days. 

**Missing Data Handling**
Seattle dataset missing precipitation values were filled with the average precipitation for that day of the year across 2018-2022.

**Processed Data**
The processed data used in this report can be found in the GitHub repository:
https://github.com/JLichwa80/weather/tree/main/data


