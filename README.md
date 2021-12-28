# bikesharing
Module 14: NY Citibike with Tableau
# Overview
The purpose of this analysis is to dertermine if the Citibike service would work in DesMoines, Iowa. We uesd tableau to analyze data from Citibike, in New York City in August of 2019. We generated visulizations of the user/subscriber ratios, the most used starting and ending locations, the breakdown of usage by gender, the checkout durations and the peak usage hours.

[link to story](https://public.tableau.com/app/profile/ryan.cramer4703/viz/Module14challenge_16406356699340/NYCCitibike?publish=yes)

## Results

![peak_hours](https://github.com/chefcramer/bikesharing/blob/main/resources/peak_hours.PNG)

This graph show the peak hours that bikes are checked out in the city. The peak hours are between 3pm and 8pm, and the lull hours are between 2am and 5am. This indicates the best time to perform maintainance on the bikes is very eary in the morning and all bikes need to be ready for usage by the mid-afternoon.

![checkout_times](https://github.com/chefcramer/bikesharing/blob/main/resources/checkout%20time.PNG)

This graph shows the average duration of indiviudal bike usage. The vast majority of rides are under an hour, and the majority of those are under half an hour, and the peak being only 5 minutes. This indicates that most rides are VERY short distances, presumably used as a quick service for a commute to and from work, and making quick trips around the city where public transportation would be much slower.

![gender_breakdown](https://github.com/chefcramer/bikesharing/blob/main/resources/gender_breakdown.PNG)

This chart shows the break down of the gender, men are the primary users.

![gender_checkout](https://github.com/chefcramer/bikesharing/blob/main/resources/gender%20checkout.PNG)

This graph shows that this service is predominantley used by males, and that the short trip trend noted above continues here.

![trips_weekday](https://github.com/chefcramer/bikesharing/blob/main/resources/trips_weekday.PNG)

This graph shows the usage of bikes day to day, broken down by 24 hours. It shows peak usage on week days, between 8 and 9 am and then again between 5 and 7 pm. This indicates that these bikes are being mostly used to commute to and from work. 

![trips_gender](https://github.com/chefcramer/bikesharing/blob/main/resources/trips_weekday_gender.PNG)

This graph also shows that males are the ones who use this service the most. This graph also shows that the peak useage is still between 8-9am and 5-7pm, for both males and females. There is a small data set for the 'unknown' gender, but it shows that the peak day is Saturday, perhaps showing that tourists without a profile (showing up as unknown) use the bikes on the weekend.

![users_gender](https://github.com/chefcramer/bikesharing/blob/main/resources/trips_user_gender.PNG)

This chart shows the breakdown of customers vs. subscribers as well as by gender. This backs up the analysais above, that 'unknown' customers (not subscribed to the service) are use the service the most in the customers category.

### Summary

This analysis shows that the most common users of citibike are men, that are subscibed to the service, use the bikes on weekdays, and take very shot trips, ususally under half an hour. 

There are several additional visulizations that can be performed:
- The realationship between most commonly used starting locations and user type (customers/subscribers), indicating the place that tourists are most likely to rent a bike.
- The locations of the top 5 or 10 starting and ending locations. This will indicate where the most bikes are neede to be stocked.
