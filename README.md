# Capstone
Final Capstone Project for Data Analytics Cohort 14 NSS

## Overview
Analyze data revolving Airbnb rental properties in nashville, and comparing them to Zillow's average rental pricing in the Nashville area. Analyze where the best area in Nashville will be to live in using the Nashville police incident report open data where there is the least amount of crime, the cheapest place to live, the most expensive, and the best for your buck to live.

## Datasets
Primary Dataset: https://insideairbnb.com/get-the-data/
Supplemental Dataset: https://www.zillow.com/research/data/
Supplemental Dataset: https://data.nashville.gov/datasets/Nashville::metro-nashville-police-department-incidents/about

## Key Questions
1. How much do Airbnb and Zillow Rent in Nashville differ
2. Do the cheaper areas have more incidents with crime?
3. You need a certain income to rent on Zillow, is that the same for Airbnb?
4. Do Hosts and their listings have a play in the cost of their rentals?
5. What areas are under or over the average of all Nashville rent?
6. What Crime is most popular in the areas under the average? Over?
7. What is the most expensive listing on Airbnb? The Cheapest?

## Tools Used
Python, Power BI, and Excel 

## Methodology
The data for airbnbs has more than just properties that can be rented for 30 days, most of them you cannot do that many, so I needed to clean out all listings that could not be rented for 30 days. 
The Zillow and Incident reports datasets had given locations of town, city, state, zip code and longitude and latitude, but the airbnb only had longitude and latitude, so I needed to convert those cooridinates to zip codes to compare with zllow rent and to see what incidents happen in those areas. 
Since the Incident reports is based off how they are filed by people there can be faults if they know where something they reported was actually correct, some of the incident reports did not not have fully finished coordinates, or some none at all, so we needed to clear the data that due to human error was not finished of the incident reports. 
The pricing was not for thirty days on airbnbs it would price per night, so I needed to convert the pricing to what it would be for thirty nights minimum, and those as well some did not have pricing due to the place not beng available at the time, so it does not show the price, so 




