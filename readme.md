# Data Analysis/Data Visualization Report: Bike Ride Trends and Biker Types of Ford GoBike System
# The Communication Data Findings Project as a part of the Udacity Advanced Data Analyst Nano-Degree Program is focusing on exploratory data 
# Visualization and explanatory data visualization.
## by Sherif Sakr
## Cairo, Egypt


## Dataset
This document explores the Ford GoBike's trip data for the public containing bike rides from April FY2019. The attributes included the trip start/end time, as well as additional measurements such as user type, gender, and age. 16K data points were removed from the analysis due to missing values in some fields, data inconsistent, or outliner issues.

Bay Wheels is a regional public bicycle sharing system in San Francisco Bay Area, California. It is operated by Motivate in a partnership with the Metropolitan Transportation Commission and the Bay Area Air Quality Management District. Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States. It was established as Bay Area Bike Share in August 2013. As of January 2018, the Bay Wheels system had over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose.
However, in June 2017 the system was officially re-launched as Ford GoBike in a partnership with Ford Motor Company. After Motivate's acquisition by Lyft, the system was renamed to Bay Wheels in June 2019.


## Summary of Findings
1- From the start time hour, the time 8:00 AM and 5:00 PM are the two peak hours which have most bikers.
2- From the days of the week, Thursday has the most bikers, compared to other days.
3- Trip duration is mostly centered on values that are less than 2000 seconds with a peak of around 600 seconds. 
4- It seems to be that the distribution of both start stations and end stations are the same.
5- Most bikers are between 25 to 40 years old.
6- There are 153,736 subscribers and 16,256 customers as user types, which represents 90% and 10% respectively.
7- In member gender, there are 126,311 male, 40,098 female, and 3,583 other, which representing 74%, 24%, 2% respectively.
8- An 8:00 AM and 5:00 PM have the highest customer and subscriber bikers across seven days, twenty-four hours.
9- Thursday has the most 'Subscriber' and 'Customer' bikers compare to other days.
10- Most 'Customer' and 'Subscribers' bikers are male.
11- Thursday, 5:00 PM has the highest biker counts across 7 days, 24 hours.

## Key insights for presentation
I'm most interested in figuring out how trip duration is dependent on other features such as age, start station, end station, user type, and gender.
I expect that trip duration will have the strongest effect on each the start stations and end stations becouse the crowded places should receive more rides.
I also think that user type, age, and gender will have effects on trip duration.
I may also that start time, and end time will have effects on trip duration.
The trip duration takes a large amount of values and is concentrated at 600 seconds peak occurred starting from 0 and then distribution starts to dip and there is no more peak value.
The maximum of member ages are 143 years old, it is unusual, so I need to remove the outliers, the member ages greater than 60 years old.
The plotting of distribution of age reveals that it more concentrated between 25 to 42 years old.
From the start time hour, the time 8:00 AM and 5:00 PM are the two peak hours which have most bikers.
It seems to be that the distribution of both start stations and end stations are same.
The Biker subscribers and customers are representing approximately 90% and 10% percentage, respectively. However, the number of subscriber is 153736 and the number of customer is 16256.
The male bikers are about three times of female bikers. However, the number of male is 126,311 with percentage of 74%, the number of female is 40,098 with percentage of 24%, and the number of other is 3583 with percentage of 2%.
When investigating the Birth year variables, Birth year is converted by substracting the year from current year 2021 in order to give the distibution for age and better perception.
Furthermore, start station and end station is plotted in a larger plot so that it gives a better insight regarding traffic of bikes at certain stations.

