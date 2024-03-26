# NYC Car Collisions Analysis

## View my Tableau Dashboard! [NYC Car Collisions](https://public.tableau.com/app/profile/jason.shan6322/viz/NYCCarCollisions_17096005773020/NYCDashboard)

![image](https://github.com/jsonshan/NYC-car-accidents/assets/122257933/428888fc-f4f0-4739-9cbc-b72a2ccc234a)

### Project Overview:
This project will show my skills in analyzing and visualizing NYC vehicle collision data collected over the past 6 years. I decided on this project because I commute daily to the city and was extremely interested in understanding the frequency and
factors contributing to vehicle accidents. By analyzing car accidents, I seek to find trends and gain a deeper understanding of vehicle collisions that occur in NYC.

My objective in the exploration is to find ways to prevent vehicle accidents and expose the dangers of car accidents.

### Recommendations
1. **Vehicle Type-Specific Initiatives**: Develop targeted initiatives aimed at sedan and SUV drivers, as these vehicles are the majority involved in car accidents. This could include educational programs focused on handling these vehicles and strategies for minimizing collision risks.

2. **Seasonal Safety Campaigns**: Launch seasonal safety campaigns targeting the spring and winter months, which are identified as the seasons with the highest number of car crashes

3. **Public Awareness Campaigns**: Since driver inattention/distraction is identified as the number one cause of vehicle accidents, consider launching ads and events that promote safe driving practices

4. **Infrastructure Improvements**: Work with city authorities to identify and address infrastructure issues in Brooklyn, the borough with the most car crashes. This might involve improving road signs, fixing traffic signals, and initiating road maintenance

5. **Seasonal Safety Campaigns**: Launch seasonal safety campaigns targeting the spring and winter months, which are identified as the seasons with the highest number of car crashes

6. **Increased Emergency Services**: Deploy additional police and emergency medical personnel to areas prone to frequent car collisions

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


### Challenges/Limitations:
Using the API to grab 2000 rows of data portrayed an inaccurate picture of NYC car collisions, so I used the latest 500,000 recorded data points, which meant I couldn't upload the Excel
file to Git Hub.

I didn't remove null values as I thought it was unnecessary for the information I was trying to find which led to my Tableau having included NULL values in my visualizations

Using 1,000,000 data points made cleaning, transforming, and dealing with special values difficult. 
