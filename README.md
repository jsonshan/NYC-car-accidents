# NYC Car Collisions Analysis


## Project Overview:
This project will show my skills in analyzing and visualizing NYC vehicle collision data collected over the past 6 years. I decided
on this project because I commute daily to the city and was extremely interested in understanding the frequency and
factors contributing to vehicle accidents. By analyzing car accidents, I seek to find trends and gain a deeper understanding of vehicle collisions
that occur in NYC.


## Results/Findings:
Vehicle accidents most frequently occur between the morning and afternoon

Brooklyn is the borough with the most car crashes

Seasons with the most car crashes are:
- Spring (the most)
- Winter
- Autumn
- Summer (the least)

Sedans and SUVs are the majority of car accidents in NYC

Driver Inattention/Distraction is the number one cause of vehicle accidents


## Data Sources:
Source: My source was taken from NYC Open Data [Motor Vehicle Collisions](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95/about_data).

This place has many public datasets from NYC and many datasets are updated every day and are free to use

## Tools:
- Python - Data Cleaning and Analysis
  - Libraries - NumPy, Pandas, Seaborn, and Matplotlib
- Tableau - Visualization tool
  - Used aggregate functions, calculation fields, and maps
 

## Data Cleaning/Preparation:
Data was cleaned and transformed with VSCode using Python. 

- Loading and inspection of the data
- Removing Duplicates
- Dropped unneeded columns
- Renaming column headers for easier transformation and understanding of data
- Added columns **season** and **time_of_day** to perform analysis

## Data Analysis:
Interesting findings and code performed 

Total Injured Percentage: 75.6006
Total Deaths Percentage: 0.3844




## Problem Statement:
1. What is the average of getting injured or killed in a vehicle collision?
2. What time of day do car crashes happen regularly?
3. What are the most common vehicles that get into car accidents?
4. What time of year do car crashes most frequently occur?


## Challenges/Limitations:
Using the API to grab 2000 rows of data portrayed an inaccurate picture of NYC car collisions, so I used the latest 500,000 recorded data points, which meant I couldn't upload the Excel
file to Git Hub.

I didn't remove null values as I thought it was unnecessary for the information I was trying to find which led to my Tableau having included NULL values in my visualizations

The dataset had over 2 million collisions recorded, which I had to limit to the most recent 500,000 data points collected as I couldn't save such a big Excel file (limited to 2,000,000 rows)
