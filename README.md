# Bike-sharing

## Overview of the statistical analysis: <br>

This analysis provides factual statistics derived from a successful bike-sharing program in New York City, Citi Bike.
By use of these statistics, there is an opportunity to replicate a successful program in Des Moines as well. <br.
To ensure this business proposal is successful, the analysis was created using Tableau and data used from August 2019 which would provide full bike usage data during the warmer months.  This will provide visualizations to assist potential investors and encourage their decision making.<br>


## Results:<br>

The trip duration data from Citi Bike has been converted to date/time format to be able to micro analyze the bike usage and trip duration further within a week.  Using 7 data visualizations, a Tableau Story has been created.

  1.  **We look at the type of customers currently using Citi Bike:**<br>
      Data shows there are currently 2,344,224 Citi Bike users.  81% of the total are annual paying subscribers and 19% are ad hoc customers.  This visualization shows there is a good base of consistent revenue for the company. <br>
      ![customer_type](https://user-images.githubusercontent.com/75437852/113071641-2dd3b000-9193-11eb-93eb-5ac593c32975.PNG) 
      <br>
      
  2.  **Checkout times based on bike users**:<br>
   Based on this line graph, the average trip duration for users are between 5 to 40 mins.  With a peak of approx. 150k bikes that are rented for the duration of about 10 minutes only.  The graph provides filter based on hours of the day.<br>
  ![checkout_times](https://user-images.githubusercontent.com/75437852/113074776-b48b8b80-9199-11eb-944f-28d519691499.PNG) 
  <br>
  
  3. **Checkout times based on gender:** <br>
  Similar to the line graph above, however segregated based on gender.  This graph identifies male users are the primary bike renters that checkout a bike between 5 - 40 minutes; peaking at 10 minutes.  Female users are approx. 67% less than male users with a similar peak of 10 minute duration, however there are more female users that continue for an additional 10 minute duration. <br>
  The gender type "Unknown" have a different duration pattern.  Lower number of users but consistent in checkout times between 5 to 25 minutes. <br>
  ![checkout_by_gender](https://user-images.githubusercontent.com/75437852/113182802-52766900-9221-11eb-8597-bdd09e28b119.PNG)
 <br>
 
  4.  **Average duration of biking trips:**<br>
  An area chart showing the average duration based on age.  The younger population between the ages of 20 - 39 are more likely to have longer trip durations.  There is a peak in longest trip duration for any users born in 1970 (39 years). <br>
 ![avg_trip](https://user-images.githubusercontent.com/75437852/113182924-7043ce00-9221-11eb-8aeb-bfec2861b872.PNG)
 <br>
    
  5.  **Trips in the week - per hour:** <br>
   This heatmap shows a pattern throughout the week of bike usage per hour.  The data shows heavier bike usage consistently Monday through Friday from 7am to 9am and again from 5pm to 7pm; these times are typically the "rush hour" of majority people going and coming from work.  Bike rentals range between 20,000 to 40,000 during the peak hours of the week.<br>
  During the weekends (Saturday and Sunday) the peak times of usage are between 11am to 7pm, however Saturday bike rentals range in the higher 20,000 and sunday a lower range of 20,000.<br>
 ![trips_weekday](https://user-images.githubusercontent.com/75437852/113183073-9d907c00-9221-11eb-8c77-bad5a1983d3c.PNG)
 <br>
 
  6.  **Trips in the week - per hour - by gender:** <br>
  Similar to the heatmap above, however segregated by gender.  As shown, male users are primary users than females.  <br>
 ![trips_gender](https://user-images.githubusercontent.com/75437852/113183029-923d5080-9221-11eb-9628-79f5a8c4e37e.PNG)
<br>
  
  7.  **User trips in the week - by gender:** <br>
  This heatmap shows bike usage by customer types and filtered by gender.  For subscribers, male users are primary than females and unknown.  Bike usage are heavier during the weekdays, peaking on thursdays. For customers, it is consistent for all gender types, however there are more usuage on weekends vs. weekdays.  This could mean tourists but also some local populations that do not subscribe to an annual membership but has usuage based on their need.
 ![trips_users](https://user-images.githubusercontent.com/75437852/113183106-a8e3a780-9221-11eb-8c35-95ebc79f7155.PNG)
<br>
 
## Summary:

Based on this entire analysis, there is sufficient demand since there are more local users subscribed for the annual membership; there is definitely a need for bike-share program in a city.  It is safe to assume users use the bike-share program as their primary mode of transportation. There are more male riders than females and this program is suitable for all ages.  <br>
Depending on an individuals need, bike share could be more affordable.  A monthly pass with Citi Bike costs $15/month.  A ride pass with the NYC transit costs $127/month.  Bike share provides more flexibility as well as other benefits not only to the local population but also to tourists.  It allows tourists to travel from point a to b while exploring the city. A day pass can be purchased for their leisure.<br>
Further analysis can be done to:
  1.  To determine a 6 months span of bike usuage.  The above analysis has been focused on one of the busier months, naturally due to better weather.  But an analysis from Jan - June would also show pertinent realistic results for winter months.  This would help determine the percentage difference between the 2 different customer types and the bike usuage by gender and or day of the week.  It can provide insight to see if ad hoc customers lower in winter months.
  2.  Another analysis can be done on the top starting stations by their start times.  This will help determine if the stations cater to the local population or the tourist crowd.  By identifying such stations, it will assist in understanding the ideal locations (and the aimed crowd) for each station in Des Moines.  And number of bikes required to meet that demand at each station.<br>

[Link to Tableau Story](https://public.tableau.com/profile/tarana.hassan#!/vizhome/Citibike_16169566754060/NYCStory?publish=yes)
