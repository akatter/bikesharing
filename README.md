# bikesharing - Module 14 Challenge

## Overview of Bike Sharing Analysis

The purpose of this project is to complete an analysis of a potential bike sharing program in Des Moines by analyzing data used by the CitiBike service in New York City. The main objectives for this analysis are to show:
- The duration that bikes are checked out for all riders, filtered by gender
- The number of bike trips for all riders for each hour of each day of the week, filtered by gender
- The number of bike trips for each type of user and gender for each day of the week

The data taken from Citibike is transformed to allow Tableau to be used for analysis by editing the datetime data.


## Resources Used
- Data Source: 201908-citibike-tripdata.csv [not included on github, but can be downloaded from https://ride.citibikenyc.com/system-data for August 2019]
- Software: Python 3.7.6, Visual Studio Code 1.63.2, Conda 4.11.0, Jupyter Notebook 6.4.6, Tableau Public

## Analysis and Results

### Tableau Story

The Tableau analysis was completed and uploaded to Tableau Public, which can be found here. 
[Link to Dashboard](https://public.tableau.com/app/profile/abdon6252/viz/NYCCitiBikeModule14AK/Story1)

### Results

Seven Visualizations were used to display information on the project. Some of these observations are reproduced on the Tableau Story.

1. Subscriber Data: The subscriber data visualization shows a bit more then 75% of the rides are taken by subscribers to the service. 

2. Gender Breakdown: As gender breakdowns are common for this analysis, an indication of gender is important to establish. More then half the users are male, with about a quarter identifying as female.

3. Checkout Times for Users: Checkout Times show a large preference of shorter trips, peaking at about 5 minutes, and the majority of trips under 20 minutes. Very few last past an hour.

4. Gender Breakdown of Previous: Gender does not have a large impact on the duration of trips, each showing similar trends. The unknown gender shows a different trend compared to the male and female lines.

5. Trips by Weekday for Each Hour: Peaks in the morning and at the end of the workday during weekdays are as expected, while weekends have a more even distribution that start later in the morning. There is a noticeable low point on Wednesday afternoons compared to the other workdays.

6. Gender Breakdown of Previous: While the Male and Female trends show similar trends, the unknown heatmap does show more of a preference to weekends and very little weekday activity.

7. User Trips by Gender and Usertype: Male subscribers show the most use of the system, and the low point on Wednesdays is shown by males and female users. Customers, rather then subscribers, show a preference to weekends.

## Summary

Overall, the breakdowns by gender do not show a large difference on information for male and female users. The majority of traffic for both are still shorter trips for work from Monday to Friday in the morning and afternoons. They show similar trends for most of the data, both with the unexpected lul on Wednesday afternoons, potentially attributed to "hump day" fatigue or perhaps something specific to New Yotk City that may need to be investigated,  such as other transportation inititaves that may focus on Wednesdays. 

Both genders also showed that shorter trips were the most common, peaking at about five minutes. Population density in Des Moines and placement of bikes should reflect the popular and most common durations.

However, those with an unidentified gender, which may correlate the most with regular customers over subscribers, actually do represent a decent amount of the weekend users. They also showed a different trend of trip users

One potential future visualization is breaking down the customer data more, seeing how they breakdown between genders and durations. While subscribers are a large part of the users on weekdays, analyzing the non-subscribing customers may help identify how to capture more customers on weekend trips, exposing them to the service and potentially creating more subscribers.

Another potential visualization is combining birth year against the total trip count. This analysis can help breakdown the potential use by age groups and could factor in methods of school transportation for users under 18, or University/College or other post-secondary education methods. This can support initiatives to see if offfering student rates and promotions could push more users to the service.