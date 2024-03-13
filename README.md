# NYC Car Collisions Analysis

## View my Tableau Dashboard! [NYC Car Collisions](https://public.tableau.com/app/profile/jason.shan6322/viz/NYCCarCollisions_17096005773020/NYCDashboard)

### Project Overview:
This project will show my skills in analyzing and visualizing NYC vehicle collision data collected over the past 6 years. I decided on this project because I commute daily to the city and was extremely interested in understanding the frequency and
factors contributing to vehicle accidents. By analyzing car accidents, I seek to find trends and gain a deeper understanding of vehicle collisions that occur in NYC.

My objective in the exploration is to find ways to prevent vehicle accidents and expose the dangers of car accidents.


### Findings:
Vehicle accidents most frequently occur between the morning and afternoon

Brooklyn is the borough with the most car crashes

Seasons with the most car crashes are:
- Spring (the most)
- Winter
- Autumn
- Summer (the least)

Sedans and SUVs are the majority of car accidents in NYC

Driver Inattention/Distraction is the number one cause of vehicle accidents


### Data Sources:
Source: My source was taken from NYC Open Data [Motor Vehicle Collisions](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95/about_data).

This place has many public datasets from NYC and many datasets are updated every day and are free to use

### Tools:
- Python - Data Cleaning and Analysis
  - Libraries - NumPy, Pandas, Seaborn, and Matplotlib
- Tableau - Visualization tool
  - Used aggregate functions, calculation fields, and maps

 
### Problem Statement:
1. What is the average of getting injured or killed in a vehicle collision?
2. What time of day do car crashes happen regularly?
3. What are the most common vehicles that get into car accidents?
4. What time of year do car crashes most frequently occur?


### Data Cleaning/Preparation:
Data was cleaned and transformed with VSCode using Python. 

- Loading and inspection of the data
- Removing Duplicates
- Dropped unneeded columns
- Renaming column headers for easier transformation and understanding of data
- Added columns **season** and **time_of_day** to perform analysis

### Data Analysis/Results:
Interesting findings and code performed 

What is the average percentage of a person getting injured in a car accident?

|Injured|Percentage|
|-------|----------|
|Persons|38.177|
|Pedestrians|6.003|
|Cyclists|3.762|
|Motorists|27.659|

What is the average percentage of a person getting killed in a car accident?

|Killed|Percentage|
|-------|----------|
|Persons|0.1948|
|Pedestrians|0.0858|
|Cyclists|0.0178|
|Motorists|0.086|

Total Injured Percentage: 75.6006

Total Deaths Percentage: 0.3844

Top 10 Factors for Car Accidents

![car-accidents-factor](https://github.com/jsonshan/car-accidents/assets/122257933/4b8039ae-7e58-4829-98fc-e2aaaa33e08d)

Top 10 Vehicles involved in Car Accidents

![common-vehicles](https://github.com/jsonshan/car-accidents/assets/122257933/f2cb197f-fb8f-484a-b856-87c6be286990)

What times do car accidents most frequently occur?

![time-of-day](https://github.com/jsonshan/car-accidents/assets/122257933/5e93795c-dee7-4081-963f-2b679fb552da)

Which borough has the most car accidents?

![boroughs](https://github.com/jsonshan/car-accidents/assets/122257933/658ac5e2-8af4-4568-9d3e-ac090adc2b72)

Which time of year or season has the most car crashes?

![seasons](https://github.com/jsonshan/car-accidents/assets/122257933/9742b06c-505a-4dc5-86dc-0cfe5c4cd47a)

### Recommendations
The number one factor in vehicle collisions is the driver's inattention/distraction, almost four times as much as its runner-up. To prevent more car collisions, the driver and civilian should be more alert, especially during the mornings and afternoons when car crashes occur most frequently.

Spring, then winter tends to have the most vehicle collisions. We could explore further and see the particular reasoning such as weather conditions and holidays.   

Brooklyn should have more policemen, ambulances, and hospitals on call. For comparison, Brooklyn has over 10 times more car crashes than Staten Island, so we should bring help to the areas with the most car accidents. 



### Challenges/Limitations:
Using the API to grab 2000 rows of data portrayed an inaccurate picture of NYC car collisions, so I used the latest 500,000 recorded data points, which meant I couldn't upload the Excel
file to Git Hub.

I didn't remove null values as I thought it was unnecessary for the information I was trying to find which led to my Tableau having included NULL values in my visualizations

Using 500,000 data points made cleaning, transforming, and dealing with special values difficult. 
