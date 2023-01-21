# Bikesharing with NYC CitiBike Data

## Overview of Analysis
### Purpose
The purpose of this analysis is to analyze bikeshare data from CitiBike in New York City for presentation to investors looking to begin a bikeshare program in Des Moines, Iowa. This was done through the use of data visualization tools in order to explore the viability of a bikeshare program in Iowa

**Key questions needing to be answered:**
- How long bikes are checked out for all riders and Genders
- How many trips are taken by the hour for each day of the week for all riders and genders
- What days of the week a user might be more likely to checkout a bike, by type of user and gender

### Resources
- Data Source: [Citi Bike Data](https://citibikenyc.com/system-data), [201908 Citibike Trip Data](https://s3.amazonaws.com/tripdata/index.html)
- Python
- Anaconda Navigator and Jupyter Notebook
- Tableau Public



## Results
### Tableau Analysis
Full storyboard/dashboard can be found at: [Link to Dashboard](https://public.tableau.com/app/profile/paola.rivas4427/viz/Module14_Bikesharing_16742556453380/NYCCitiBikeStory)

### Bikesharing Data Visualizations for NYC Citi Bike (August 2019)

**Checkout Times for Users**
![Checkout Times for Users](https://github.com/pfrivas/bikesharing/blob/main/Images/Checkout%20Times%20by%20Users.png)

Charting the checkout times for users helped visualize that:
- The majority of trips taken are under an hour in length. 
- Most trips are under a half-hour in length
- There is a large dropoff in number of rides over an hour in length.

**Checkout Times by Gender**
![Checkout Times by Gender](https://github.com/pfrivas/bikesharing/blob/main/Images/Checkout%20Times%20by%20Gender.png)

Charting the checkout times for gender helped visualize that:
- This is the breakdown of number of rides by duration, separated by gender
- The majority of rides are taken by male-identifying customers.
- Female-identifying customers are almost 3 times less that those identifying as male

**Trips by Weekday for Each Hour**
![Trips by Weekday per Hour](https://github.com/pfrivas/bikesharing/blob/main/Images/Trips%20by%20Weekday%20for%20Each%20Hour.png)

Charting the trips by weekday per hour helped visualize that:
- The heatmap reinforces how much of the userbase uses CitiBike bikes during their workday commute
- The heatmap shows the busiest times are 5pm - 6pm on Thursday
- The heat map also shows how the busiest day, all day to rent a bike is Saturday 

**Trips by Gender (Weekday per Hour)**
![Trips by Gender_Weekday per Hour](https://github.com/pfrivas/bikesharing/blob/main/Images/Trips%20by%20Gender%20(Weekday%20per%20Hour).png)

Charting the trips by gender by weekday per hour helped visualize that:
- The male identifying users take significantly more rides than the female identifying users
- Overall all genders tend to ride at the same times
- Wednesday seems to be the least busiest weekdays for both genders

**User Trips by Gender**
![User Trips by Gender](https://github.com/pfrivas/bikesharing/blob/main/Images/User%20Trips%20by%20Gender.png)

Charting the user trips by gender helped visualize that:
- The heatmap reinforces how much of the userbase is dominated by male-identifying users
- The heatmap also shows the majority of the user database are subscribers
- There are hardly any subscribers that do not identify their gender

**NYC Dashboard with Customer Demographics**
![Customer Demographics](https://github.com/pfrivas/bikesharing/blob/main/Images/Customer%20Demographics.png)

Creating a dashboard with customer demographics and top starting locations helped visualize that:
- Subscribers make up the majority (over 3/4) of the customer database and are regular bike users
- The majority of Citi Bike users are Male (~ 60%)
- The younger users tend to take longer bike rides on average than the older users

**Bikesharing Peak Hours for the Month of August**
![Peak Hours](https://github.com/pfrivas/bikesharing/blob/main/Images/Peak%20Hours.png)

Charting the peak hours for the month of august helped visualize that:
- The most common times of bike usage or during rush hour (before and after work)
- The least common times of bike usage are between the hours of 3 - 4am
- From 10am to 5pm the amount of bike usage gradually increases

**Bike Maintenance**
![Maintenance](https://github.com/pfrivas/bikesharing/blob/main/Images/Bike%20Utilization%20and%20Maintenance.png)

Charting the usage of bikes and ending locations helped visualize that:
- The most common ending locations are in metropolitin areas with the most common location having 16,455 rides end there.
- The most used bike had over 1000 hours of usage
- The bike with the most trips had 479 rides logged

## Summary

### Key Results
For the month of August in NYC, there was a total of 2,344,244 bike rides. The most common users of CitiBike bikes are male-identifying subscribers and the most common locations for rides are in large metropolitan areas. Most rides are less than an hour long. Peak usage is during morning rush hour (8am-10am) and end or work day rush hour (5pm-6pm) commute times. The lowest usage hours are between 3 AM and 4 AM. These hours would be the best times to conduct bike repairs and redistribution of bikes from the most populated stations to less populated stations. The most common workday for rides is Thursday and the most common day overall for rides is saturday.

### Additional Visualizations
- Comparing data across different months to visualize trends throughout the entire year
- Comparing whether data to find the correlation between the whether and the rides
