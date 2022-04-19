# Bike Sharing Challenge

## Overview of the analysis

For this project and to conduct extensive bike trip analysis requested we: (1) used Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype in tableau created a set of visualizations to:

(2) Show the length of time that bikes are checked out for all riders and genders
(3) Show the number of bike trips for all riders and genders for each hour of each day of the week
(4) Show the number of bike trips for each type of user and gender for each day of the week.

Finally, with these new visualizations in addition to the ones created in the tablewau module I created a final presentation and analysis to pitch to investors.

## Results

Below are the visualizations created with a description of what is being shown for each of them:

### Checkout Times for Users

![image](https://user-images.githubusercontent.com/96096924/163912754-2f9dd49c-296a-45bb-adcf-1a4b80f7a2dc.png)

The graph shows the duration of bike trips. In short most trips are shorter than 60 min and for the most part shorter than 20 min with the most frequent length being 6 min. So what the graph shows us that the trip durations are short in nature. 
Link: https://public.tableau.com/app/profile/sebastian.llados.vila/viz/CitiBikeChallenge_16503340527170/TripDurantion?publish=yes

### Checkout Times by Gender

![image](https://user-images.githubusercontent.com/96096924/163912827-35bfc7ad-641b-4472-b7d2-0046df069963.png)

Same as above but we added the gender component to the analysis. You can see the curves are similar with peak for males at 5 min and femaales at 6 min. The unkown has a little bit less clear peak between 7 and 24 minuntes. But overall across the board trips are short across genders. 
Link: https://public.tableau.com/app/profile/sebastian.llados.vila/viz/CitiBikeChallenge_16503340527170/TripDurationbyGender?publish=yes

### Trips by Weekday for Each Hour

![image](https://user-images.githubusercontent.com/96096924/163912895-7a67b3a2-442c-47f0-8228-aaeaafe6c76b.png)

This graph shows with the color intensity the number of rides per day and hour. In summary weekdays peak are commute hours in early morning and afternoon with Friday afternoon exit hours having a wider ranger. For weekends the peak is more unclear extending from late morning to early afternoon. There is definetely a huge variance in use for weekdays between peak and non peak, not as marked in the weekend. Main peak hours are as follows:

![image](https://user-images.githubusercontent.com/96096924/163919742-d742171c-1228-44ac-85af-6b1ef2160766.png)


Link: https://public.tableau.com/app/profile/sebastian.llados.vila/viz/CitiBikeChallenge_16503340527170/PeakHoursbyWeekday

### Trips by Gender (weekday per hour)

![image](https://user-images.githubusercontent.com/96096924/163913026-9ed31e78-2497-440f-a67e-34939d65077b.png)

Same as above by split by gender showing very similar pattern for male and female and no clear pattern for other. My guess is that this is mostly filled by tourists or non subscribers and less accurate in gender identification. 

### User Trips by Gender by Weekday

![image](https://user-images.githubusercontent.com/96096924/163913115-dcdbca18-0df4-479d-9e14-af74d48dde3d.png)

Shows the nuber of trips by usertype and gender. Is clear that across days the majority of trips are from subscribers and shows stronger for male followed by female. 

### Average Trip Dimension

![image](https://user-images.githubusercontent.com/96096924/163913339-29829dda-8c37-4ec1-b9f3-9741230d64b6.png)

This graph shows that in general the younger the person the longer the trip. There are some exceptions and the difference is not significant either. 

### August Peak Hours

![image](https://user-images.githubusercontent.com/96096924/163913452-b95e90bc-686a-4407-8b17-12b6744e2c2b.png)

Peak hours are obviously in average commute hours early morning and afternoon but this is better explained by the graphs above for weekdays vs weekends. 

## Summary

In summary after all the visualizations I conclude that the subscriber model is key in the case of new york and furthermore that there are clear patterns for weekdays and weekends, first related to commute and second to middle of the day (not too early not too late). It looks like both businesses are important in this case though I would like to compare the income from subscribers in weekdays vs weekends as the next graph. Also and from a complete different dataset I would like to understand the popolation of commuters in NY vs the new proposed city and use a pentration analogy to see if the commuter business would be sufficient. We can the layer the weekend analyis. 
