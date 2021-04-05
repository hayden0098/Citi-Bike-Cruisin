# Citi-Bike-Cruisin
[link to dashboard](https://public.tableau.com/profile/hayden.chen#!/vizhome/NYC_CitiBikes_Challenge_WorkBook/Story1 "link to dashboard")

## Overview of the statistical analysis:
Prepare a business proposal for the bikes share business for hometown of Des Moines. Using the New York City bikes share data and analysis to figure out how bike-share business works in New York City. We will be using Tableau to visulize the data, Tableau Public is a powerfull tool to create visualizations locally and then upload the visualizations to Tableau Server.

## Results:
There are 7 visalizations for the NYC Citibike as the analysis result, The set of visualizations will answer the following question:

* Show the length of time that bikes are checked out for all riders and genders to see How long bikes are checked out for all riders and genders.

* Show the number of bike trips for all riders and genders for each hour of each day of the week to see How many trips are taken by the hour for each day of the week, for all riders and genders.

* Show the number of bike trips for each type of user and gender for each day of the week to see a breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.

1. The line graph shows the relation between number of Bikes and the tripduration in times format of hour and minutes. The data shows increasing trend before 5 minutes, the climaxt points is exactly at 5 minutes, then trend were declined afterward. It means most riders prefer to have short time trip, their checkout times are no more than a hour and 5 minutes.
![Checkout_Times_for_Users](https://github.com/hayden0098/Citi-Bike-Cruisin-/blob/main/images/Checkout%20Times%20for%20Users.jpg)

2. This line graph are similar to the the first graph above; "Checkout Times for Users"; but it's more detailed by adding more filters and marks the different gender in different colors line. It shows that Male are the highest number 108,087 of riders with the highest tripduration time in 5 minutes, Female are second high number 34,151 of riders with he highest tripduration time in 6 minutes, also there are smallest portion of unknown gender riders with around 10~23 minutes.
![Checkout_Times_by_Gender](https://github.com/hayden0098/Citi-Bike-Cruisin-/blob/main/images/Checkout%20Times%20by%20Gender.jpg)

3. The heat map shows the number of bike trips by weekday for each hour of the day, the most count of bike trip are in Thursday 17~18 oclock, second high are in Monday and Tuesday 17-18 oclock also in Thursday 8 oclock. The time of rider will not having trips are between 12-5 oclock. 
![Trips_by_Weekday_for_Each_Hour](https://github.com/hayden0098/Citi-Bike-Cruisin-/blob/main/images/Trips%20by%20Weekday%20for%20Each%20Hour.jpg)

4. This heat map is similar to the third graph above, but with gender in filter field. There are 3 heat map for Female, Male and Unknown. Male is the gender that in highest level of heat, Female is the second high. In gender of Female, the most count of ride is 10511 to 11336 in Thurstday at 17-18 oclock. second high of count is around 8 to 9 Thousand in Monday and Tuesday at 17-18 oclock also in Thursday 8 oclock. In gender of Male, most count of ride is around 30 Thousand in Thurstday at 17-18 oclock, second high is around 25 Thousand in the Monday, Tuesday and Friday at 17-18 oclock.
![Trips_by_Gender](https://github.com/hayden0098/Citi-Bike-Cruisin-/blob/main/images/Trips%20by%20Gender%20(Weekday%20per%20Hour).jpg)

5. This the heat map between the Weekday of different usertype and Gender Type. The data shows Male Subscriber usertype are the most count in every weekday.
![Trips_by_Gender_by_Weekday](https://github.com/hayden0098/Citi-Bike-Cruisin-/blob/main/images/Trips%20by%20Gender%20by%20Weekday.jpg)

6. This is bar graph shows the total count of ride in for every hours in the month of August. During the weekday the Count of trip start increase after 6, until reach the time of 8 drop a bit after ward. Then start increase the count at 10 till reach the other climax which is 17-18 oclock.
![August_Peak_Hours](https://github.com/hayden0098/Citi-Bike-Cruisin-/blob/main/images/August%20Peak%20Hours.jpg)

7. This is the symbol map tp visualize the top starting locations, with symbols that correlate to the numeric value of the map location. The most popular starting locations will be marked by larger symbols in deeper color on the map.
![Top_Starting_Locations](https://github.com/hayden0098/Citi-Bike-Cruisin-/blob/main/images/Top%20Starting%20Locations.jpg)

## Summary:
As the summary of the project, the total count of bike trip in August is 2,344,224 and the Male rider is the most portion that can affact the trend of data. And the peak hour is the time when people get to work at the morning and the time when they off duty at the evening. Also all rider are prefer shot trip duration, which is no more than a hour and most tripduration is in 5 minets. For the future analysis, Ｗe have 2 additional visualization suggested to make:

1. the graph that provide the relationship between the age and total count of ride.

2. the graph that can take a closer look at the top starting location and the age of rider to see about what kind of people will take the most bikes trip.
