# Pyber: A Ride Sharing Analysis

Using Python, Jupyter Notebook, Pandas, and Matplotlib to analyze city and driver ride sharing data

## Overview of Project

An analysis of city and driver ride sharing data to provide insight and comparison on urban, suburban, and rural areas. Analysis includes finding the total rides, total drivers, total fares, and average fare by ride and number of drivers.

### Purpose

As a Data Analyst for Pyber, a Python based ride sharing app company, the purpose of this project is to perform some analysis on 2019 rideshare data. Information gathered needs to include the relationship between the following areas:

- type of city 
- the number of drivers per city type
- percentage of rides by city type
- percentage of drivers by city type
- percentage and total of fares by city type
- average fare per ride by city type
- average fare per driver by city type 

V.Isualize, PyBer's CEO, will need visualizations of rideshare data using Matplotlib to help improve access to ride-sharing services and determine affordability for underserved neighborhoods.

## Results

The dataset given reflects three different types of cities: urban, suburban, and rural. Looking at the pie chart shown below, the majority of the fares collected are from urban cities at 62.7% of the total fares collected in 2019. Suburban collected 30.5% of the fares. Rural collected 6.8% of the fares.

![Fig5](https://user-images.githubusercontent.com/108373151/183270276-60a491ad-fc9f-4ede-b57c-9b62a2a9b33b.png)

Looking at the total number of rides by city type in 2019, we see a similar outcome. Rides in urban cities make up 68.4% of the total rides, 26.3% in suburban areas, and 5.3% in rural areas.

![Fig6](https://user-images.githubusercontent.com/108373151/183269049-307bff3c-c539-4bc6-8682-5344ba2bc6ef.png)

The figure below shows the number of drivers by city type. More than 80% of the drivers are employed in the urban cities. Suburban drivers are 16.5% of the total drivers and rural drivers are 2.6% of the total drivers.

![Fig7](https://user-images.githubusercontent.com/108373151/183269052-f5a5aae0-c0c6-4488-a35a-adbe17476f5f.png)

### PyBer Summary 

The following key metrics were analyzed in a dataframe to see the disparity in city types.

![PyBer_summary](https://user-images.githubusercontent.com/108373151/183268949-2c767cb2-b675-4ae1-b3a6-3627e64468bb.png)

- Total rides in rural cities at 125 rides are considerably less than the demand in urban cities at 1,625 rides. Suburban had 625 rides in 2019. 
- The majority of fares in 2019 is from urban cities at $39,854. Suburban had $19,356 in total fares and rural had $4,328 in total fares.
- The average fare per ride in urban areas at $24.53 is about $10 less than the rural cities at $34.62. Rural is in between at $30.97 average share per ride. 
- There are significantly more drivers in urban cities at 2,405 drivers than suburban and rural at 490 and 78 drivers, respectively.
- The average fare per driver is much less in urban cities at $16.57 per driver compared to $55.49 per driver in rural areas. Suburban drivers collect $39.50 on average.

### PyBer Fare Summary by Week

The "Total Fare by City Type" line graph below reflects the weekly sum of fares by city type for January 1, 2019 through April 28th, 2019. It reflects peak rideshares in each type of city.

![PyBer_fare_summary](https://user-images.githubusercontent.com/108373151/183268951-c72341d1-4320-41a5-9759-8bb4ae0f3f2a.png)

Some interesting data points to note:
- The least amount of fares were collected in Urban cities in January
- Total fares peaked in every city type around the end of February 2019
- Urban fares remained relatively high around the beginning of March
- Suburban fares peaked again at the end of April 2019

## Recommendations

- The large number of drivers (over 80% of the total drivers) in urban areas mean that each driver is earning less fares. This may reflect negatively on the company if drivers are unable to make enough money. Would consider decreasing the number of drivers in urban areas.
- The data is clear that the majority of rideshares and fares come from urban cities. Continued marketing, investments and rate specials may further increase PyBer's usage and increase revenue.
- Although demand is much less in rural areas, would recommend to increase the drivers in rural areas. Especially encourage more drivers that are willing to drive longer distances.
- Decreasing the fare rate in rural areas might encourage more people to utilize the service. Longer distances with smaller rates will still drive revenue.
- Would consider further analysis into peak times of rideshares. Information gathered in a peak time analysis would help determine if there are enough drivers to satisfy demand.