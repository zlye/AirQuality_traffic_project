The problem area:

In early 2024, Governor Kathy Hochul unlawfully blocked a plan to introduce congestion charging for drivers entering lower Manhattan. This plan aimed to reduce traffic in lower Manhattan and raise more money to expand and improve public transit. Traffic contributes to poor air quality in New York City; the worst air quality is in Manhattan. Poor air quality affects human health, causing asthma and exacerbating heart disease.

This event inspired me to create this project and ask: If the congestion pricing plant had been implemented, how much could air pollution be reduced? Or, more broadly, how would reducing traffic, both cars and trucks, reduce air pollution in Manhattan?

Impact:

My goal is to create a generalizable model that could influence the government, businesses, and policy makers in New York City. I also hope that my approach could be useful to other cities trying to improve their air quality conditions.
Brainstation Capstone project
Air quality + traffic

There are multiple data sets of varying quality in the initial exploration.
1. Car counts at a variety of locations across six boroughs from 2021 -2022
https://data.cityofnewyork.us/Transportation/Automated-Traffic-Volume-Counts/7ym2-wayt/about_data

Exploratory analysis in:
Exploratory_NYC_opendata_carcounts.ipynb

2. Department of Transportation traffic averages in locations across six boroughs 2016-2023
The main data points of interest are AADT: annual average daily traffic, and % Truck traffic
"aadt_and_truckpct.csv"

Exploratory analysis in:
Exploratory_analysis_traffic.ipynb

3. Real-time air quality fine particles (PM 2.5) acquired from the NYU.gov health portal
This is hourly air quality data from 17 locations around New York City. There are multiple air quality indicators. Currently, I have focused on PM 2.5 because this pollutant is largely caused by cars, trucks, and other combustion.

Two exploratory analysis:
Exploratory_analysis_traffic.ipynb
- Initial analysis of data from April 2016, map-making

Exploratory_air_March.ipynb
- analysis of data March 2020 and 2024

