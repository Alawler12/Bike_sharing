## Citi Bike Bikeshare Analysis with Tableau

### Analysis Overview
The purpose of this analysis was to create visualizations with Tableau that analyze the ridership of Citi Bikes in NYC to determine how successful a deployment might be in another city, Des Moines.

### Results
Here are the most pertinent visualizations created to analyize the data.

These maps show that the most popular beginning and ending locations for bike rides are mostly concentrated in the downtown Manhattan area.  This area of the city is mostly commercial rather than residential, suggesting that bike rides are most often taken by those commuting to work from their homes in the city, and tourists visiting the popular areas of town.

![start.PNG](https://github.com/Alawler12/Bike_sharing/blob/main/screenshots/start.PNG)
![end.PNG](https://github.com/Alawler12/Bike_sharing/blob/main/screenshots/end.PNG)

The vast majority of users of Citi Bike are subscribers rather than customers. This means that they pay for a monthly membership rather than pay per ride or on a daily pass.  This suggests the majority of users live in the city in which they purchased a Citi Bike membership.

![usertype.PNG](https://github.com/Alawler12/Bike_sharing/blob/main/screenshots/usertype.PNG)

The majority of users are those who identify as Male.

![gender.PNG](https://github.com/Alawler12/Bike_sharing/blob/main/screenshots/gender.PNG)

Checkout times and trip duration show that most trips are short trips, taken during rush hour.

![Checkout_times_all.PNG](https://github.com/Alawler12/Bike_sharing/blob/main/screenshots/Checkout_times_all.PNG)

![Checkout_times_gender.PNG](https://github.com/Alawler12/Bike_sharing/blob/main/screenshots/Checkout_times_gender.PNG)

Peak hours for bike trips show that the most number of bike trips are taken during the morning and evening commuting hours, particularly the evening rush hour.  This suggests that users often use Citi Bike as their means to travel between home and work.

![peak_hours.PNG)](https://github.com/Alawler12/Bike_sharing/blob/main/screenshots/peak_hours.PNG)

This graph shows that the most trips are made during the weekday, and especially during morning and evening rush hour.

![weekday_trips.PNG](https://github.com/Alawler12/Bike_sharing/blob/main/screenshots/weekday_trips.PNG)

When broken down by gender, it can be seen that users who identify as Male make more trips during the week than those who identify as Female.

![weekday_trips_gender.PNG](https://github.com/Alawler12/Bike_sharing/blob/main/screenshots/weekday_trips_gender.PNG)

This graph shows that the highest concentration of trips are taken by Subscribers who identify as Male, during weekdays.

![weekday_users.PNG](https://github.com/Alawler12/Bike_sharing/blob/main/screenshots/weekday_users.PNG)


### Summary
Analysis of the ridership of Citi Bike in August of 2019 in NYC shows that most users of Citi Bike are likely residents of NYC.  Most users are Subscribers rather than single use customers, and most trips taken on a Citi Bike are taken during the week and, more specifically, during peak commuting hours in the downtown area.  The most likely cause for this trend is that the majority of users subscribe to Citi Bike as a means to commute from home to work, and so most likely reside in NYC.

Please see my [Tableau Story](https://public.tableau.com/profile/ashley.lawler#!/vizhome/NYCCitiBikeUserAnalysis-August2019/NYCCitiBike-AugustFigures?publish=yes) for another view of this analysis.

#### Conclusion
A Citi Bike deployment in another city has a likelihood of success if the city has a downtown center within biking distance of residential neighborhoods.  Since most of the ridership is composed of monthly subscribers who use the bikes to commute to work, a deployment would be most likely to succeed in a city in which bike travel to work is possible for residents of that city.  If the city center is not accessible from residential areas, ie surrounded by highways or great distances, it is less likely that people will want to use a bike to commute to work.  The appeal of bikes to tourists and visitors to the city cannot be discounted, but since 1.9 million of the 2.3 million rides taken in August were by Subscribers, the largest ridership has been shown to be among residents.

#### Further Analysis
Further Analysis to discover more factors that could contribute to success of Citi Bike deployments in other cities could be done.  I would suggest analyzing ridership for each month of the year.  This would help determine the effect of weather/climate on ridership, which could help determine which cities would have a greater chance of success.  I would also suggest a different analysis of trip duration. The checkout times visualization displays its information in a confusing and unclear manner.  I think an analysis of average trip durations would be a much more useful communication of this data.  It would be more interesting to see the average length of trips, rather than how many trips happen each hour. This would help a city determine if their city’s layout is conducive to the length of time the average user wants to spend on a bike.
