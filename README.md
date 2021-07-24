# Communicate Data Findings
In this project, I wanted to look at the characteristics of Ford GoBike system data covering the greater San Francisco Bay area. The main focus was on days of the week, hours of the day, trip duration, user type, user age, and gender.
<br/>
It is was implemented using Python language, Pandas, Matplotlib, Seaborn, and NumPy under Data Analyst Nanodegree Program from Udacity!

# Dataset
The dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.
<br/>
The dataset can be downloaded from [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv).
<br/><br/>
The dataset contains these key columns:
- Member Year of Birth
- Member Gender
- User Type (Subscriber or Customer)
- Trip Duration(in seconds)
- Bike ID
- Bike Share for All Trip
- Start Time
- End Time
- Start Station ID
- End Station ID
- Start Station Name
- End Station Name
- End Station Latitude
- End Station Longitude
- Start Station Latitude
- Start Station Longitude


# Summary of Findings

## Univariate Exploration
- The number of bike trips is higher on work days (Monday, Tuesday, Wednesday, Thursday, Friday) and lower on weekends days (Saturday, Sunday) in San Francisco.
- The distribution of bike trips used per day hour is popular between 8-9 AM and 4-6 PM.
- The ages distribution of bike trips is most popular with the age group between 25-40 years old.
- The gender distribution of bike trips was (74.6%) are males, while females are (23.3%).
- The user types distribution of bike trips was (90.5%) are subscriber, while customer are (9.5%).

## Bivariate Exploration
- The importance of including user type in data analysis revealed that there are some differences in the behavior of customers and subscribers
- The average bike trip duration in minutes per user type was (10.679922) are subscriber, while customer are (21.847536).
- The distribution of bike trip duration in minutes per user type was the distribution of customer trip time shows more variability than subscribers.
- The number of bike trips gender per user type was a subscribers bigger than customers.
- The distribution of bike trips used per day hour was a subscribers bigger than customers.
- The number of bike trips for subscribers is higher on work days (Monday, Tuesday, Wednesday, Thursday, Friday) and lower on weekends days (Saturday, Sunday) in San Francisco.
- The number of bike trips for customers is consistent on all week days in San Francisco.

## Multivariate Exploration
- I've observed that male customers take longer bike trips than female customers.
- I've observed that males take long bike trips from 11 AM to 4 PM.
- I've observed that subscribers take long bike trips from 11 AM to 5 PM.

# Key Insights for Presentation 
In the presentation I summarized my key findings, displaying key univariate, bivariate, and multivariate plots. 
