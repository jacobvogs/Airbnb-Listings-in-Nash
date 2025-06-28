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
The pricing was not for thirty days on airbnbs it would price per night, so I needed to convert the pricing to what it would be for thirty nights minimum, and those as well some did not have pricing due to the place not beng available at the time, so it does not show the price, so I decided to convert the data frame to an excel sheet from python to find an easier way to clean out unclean data, like the dollar sign out of each price, then to multiply everything by thirty, then brought that back into python and cleaned out all NaN listings, and merged the datasets together and compared it with the zillow listing averages. 

I explored the zip codes that each dataset would list, and so I had to make sure they all had to have the same amount and the correct ones as well. 
I wanted to see the averages of Airbnb compared to Zillow, and the areas that were the highest and the areas that were the lowest. 
I then wanted to see if the Incidents in those areas had any affect on the pricing, and whether the lower had more crime or not. 
I compared the incidents from the areas that were on the lower cost of rent to the higher end areas. 
I found that Zillow mentions on their listings the income they need to rent, so i searched the data in airbnb and they have no mention of that on their listings
For fun I wanted to see the highest Airbnb pricing and the lowest and see what the differece in them. 
I made a clustered bar chart to compare the averages of zillow and airbnb rent through python
Then to find the highest incident report I used a bar chart from Power BI, and then further along used a dashboard to look into incidents specifically in 37207. 
I compared a host's count of listings to the highest listings on airbnb with bar charts from Power BI to see any correlation between the two. 
I used a bar chart with the a line of the average rent in Nashville with Airbnb using python, and added a pie chart to see the percentage of areas under the average and over the average. 
Then continued to make a horizontal bar chart on python to compare the incidents of those areas under and over the average 
I then found the highest and lowest listings of all the airbnbs listed, and showed what they looked like and why they cost the amount they listed.

I soon found out that Airbnb is super unpredictable, and that the pricing could very much fluctuate in whatever area you want to live in. Airbnb does not follow the same rules as Zillow landlords do, as they need to stay on a certain cap of rent, usually the rent in those areas with zillow are very consistent and close in pricing, while airbnb could have a very expensive rental right across the street from a super cheao one. With Airbnb you also get to stay in a wider variety of places like private rooms, guest house, or entire houses, and booking these rentals is much easier than zillow. Whether it be Zillow or Airbnb pricing the common belief that the lower cost of rent the more unsafe it is, does seem to be consistent with the data as well. 

## Visuals
Incident reports dashboard : https://app.powerbi.com/view?r=eyJrIjoiOTUxNjZlNmEtNzAzZS00Mjk1LTgyNWItNzRlM2I5NzlmODM2IiwidCI6IjEwMWRhNTg3LTE4NDMtNGY1Mi04YjhhLTE3YjA2OWM2NmQzMyIsImMiOjJ9

Other data visuals : https://app.powerbi.com/view?r=eyJrIjoiNjYzZDU5MjMtYTg1My00MTAyLWFlZTItOTQyZGQ4NGY5NGJlIiwidCI6IjEwMWRhNTg3LTE4NDMtNGY1Mi04YjhhLTE3YjA2OWM2NmQzMyIsImMiOjJ9

## Contact
[Jacob Vogelpohl] • [vogelpohljacob@yahoo.com] • [www.linkedin.com/in/jacob-vogelpohl]
