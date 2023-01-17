# Bikesharing

## Overview of the statistical analysis:

Use data from the Citi Bike program in New York City for August 2019 was retrieved from ride.citibikenyc.com. The data was transformed using pandas to change the datatype of the "tripduration" column from an integer to a datetime datatype to get the time in hours and minutes.

## Purpose

The purpose of the current analysis is to prepare visualizations that give potential investors a look into the highly-successful NYC Citibike bike-sharing program, so that they can see for themselves that a bike-sharing program in Des Moines is a solid business proposal. Among others, we have prepared visualizations that:
1) Show the length of time that bikes are checked out for all riders and genders, 
2) Show the number of bike trips for all riders and genders for each hour of each day of the week, and 
3) Show the number of bike trips for each type of user and gender for each day of the week.

[link to dashboard]([LINK GOES HERE](https://public.tableau.com/app/profile/griselda1378/viz/NYCCitiBikeDashboard_16680451684360/NYCCitiBikeDashboard))

[link to story]([LINK GOES HERE "link to story"](https://public.tableau.com/app/profile/griselda1378/viz/NYCStory_16680458689970/NYCStory#1))

## RESULTS

The results of our analysis have been incorporated into a story on Tableau Public

POINT #1 - Comparing visualizations for the 'Top Starting Locations' and 'Top Ending Locations', we can see that the most active starting locations are also among the most active ending locations. This is important, because we need to know whether there might be an excess or shortage of bikes at particularly stations over time.

POINT #2 - Looking at visualizations for 'Checkout Times for Users' and 'Checkout Times by Gender', we see that most rides are for 20 minutes or less, and that the vast majority of rides are less than one hour. We also see that this pattern is the same regardless of gender.

POINT #3 - The 'Gender Breakdown' pie chart shows that males in NYC utilize the bikesharing program almost 3 times as often as females. Further analysis is needed to understand why this is the case.

POINT #4 - The heatmap of 'Trips by Weekday per Hour' shows a clear pattern of bicycle useage 
1) during the morning weekday commute (7-9 a.m.), 
2) during the evening weekday commute (4-7 p.m.) except on Wednesday evenings, and 
3) all day long on weekends.

POINT #5 - The 'Trips by Gender (Weekday per Hour)' heatmap shows that the useage pattern is true regardless of gender, although the total numbers for males is considerably higher.

POINT #6 - The 'User Trips by Gender by Weekday' heatmap demonstrates the following points: subscribers are mostly male and account for most of the weekday activity, customers' gender are often unknown, and useage on the weekend is more evenly split between subscribers and customers.

POINT #7 - Our 'Bike Utilization' and 'Bike Repairs' charts show that some bikes are used for many trips and many total hours, while other bikes are hardly used at all. More analysis is called for to assess whether there are predictable patterns of use for high- or low-use bikes.

## SUMMARY

The results of this analysis have given insight into the utilization of bicycles in the NYC Citibike bike-sharing program. We've seen the patterns of useage by time and by gender. Utilization rates can now be predicted based on time of day and location. Weekday useage is heavily concentrated around the morning and afternoon commute. Weekend useage is more evenly spread through the day. We would recommend further analysis for a few points. Firstly, while we've seen that the vast majority of trips are 30 min or less, we should perform further analysis to compare weekend trip durations to weekday trip durations. We should also look further into the patterns of useage for the bicycles that see the heaviest use, perhaps preparing maps showing all of the starting/ending routes/locations for the heaviest use bikes. We should also prepare a visualization to determine if there are specific locations that are completely unused.
