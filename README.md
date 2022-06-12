# bikesharing

## Overview of the analysis

An analysis and visualization of Citi Bike data (New York City, NY, USA) was performed in Tableau using data that has been released to the public (2019 August). The goalof this project was to identify trends that can be presented to investors to start a ride sharing business in Dse Moines, Iowa, USA.

In Tableau, a variety of data sources including live data can be used. The data can be dimensions or measures, and visualizations are created using worksheets. Dashboards can be created using worksheets. Worksheets and dashboards can be used to build a story for presenting. In this project, a story was created and published into Tableau public site.   

A CSV file containing the Citi Bike dataset for 2019 August was downloaded from their webpage ([Link](https://ride.citibikenyc.com/system-data)) and the Trip Duration column was converted from number into date-time format using Pandas in Jupyter Notebook, and the Pandas datafram was exported into a CSV file. This file was imported into Tableau for visualization.


Tools:
- Tableau Public
- Jupyter Notebook 
- Python 3.7
- Git

## Results: Using the visualizations you have in your Tableau Story, describe the results of each visualization underneath the image.

There were a total of 2,344,224 (~2.3M) bike rides and 146,752 bikes were used.  

**Length of time that bikes are checked out for all riders and genders**

The trip duration is within 60 minutes (one hour), with a peak time of 5-6 minutes for males and females (it varied between 7-2x minutes for those with no records for gender). See Figure 1 anf Figure 2. There were ~XX, ~YY, and ~ZZ bike riders (Figure 3).   

**Starting and destination Hubs**

It is apparent that there are some starting (Figure 4) and destination locations (Figure 5) that were popular. 

Show the number of bike trips for all riders and genders for each hour of each day of the week
Show the number of bike trips for each type of user and gender for each day of the week.
Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors.




[Link to Dashboard in Tableau](https://public.tableau.com/views/Module14-Challenge_16544762101330/BicycleSharing?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)


[Link to Story in Tableau](https://public.tableau.com/views/Module14-Challenge_16544762101330/BikeSharing?:language=en-US&:display_count=n&:origin=viz_share_link)

![Checkout time](/images/checkout_time_for_users.png)


**Figure 1**. Trip duration for the bikes checked out  


![Checkout time by gender](/images/checkout_times_by_gender.png)

**Figure 2**. Trip duration for the bikes checked out (by gender)    


![Gender](/images/gender_breakdown.png)

**Figure 3**. Breakdown of trips by gender


![Starting hubs](/images/starting_hubs.png)

**Figure 4**. XX  


![Destination hubs](/images/destination_hubs.png)

**Figure 5**. XX  


![Trips by user weekday by hour](/images/trips_by_week_day_by_hour.png)

**Figure 6**. XX  


![Trips by gender](/images/trips_by_gender.png)

**Figure 7**. XX  


![User trips by gender by weekday](/images/user_trips_by_gender_by_weekday.png)

**Figure 8**. XX  


![Trips by user type](/images/trips_by_usertype.png)

**Figure 9**. XX  


![Trips by user type by birth year](/images/trips_by_usertype_by_birthyear.png)

**Figure 10**. XX  


## Summary: Provide a high-level summary of the results and two additional visualizations that you would perform with the given dataset.


