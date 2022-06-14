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

LINKS TO LARGE CSV FILES: 1. [Original File](https://github.com/wwpa65/Files_LFS/blob/19b2b5f9791826aeeaea719758fb15ea8ea4a82d/201908-citibike-tripdata.csv)
2. [Converted File](https://github.com/wwpa65/Files_LFS/blob/19b2b5f9791826aeeaea719758fb15ea8ea4a82d/201908-citibike-tripdata_converted.csv)

The Dashboard and the Story was saved in thr Tableau Public site.
- Link to the Project: [Bike Share Project](https://public.tableau.com/views/Module14-Challenge_16544762101330/TripsbyGender?:language=en-US&:display_count=n&:origin=viz_share_link)

- Link to the dashboard: [Bicycle Rides](https://public.tableau.com/views/Module14-Challenge_16544762101330/BicycleSharing?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

- Link to the Story: [Bike Share](https://public.tableau.com/views/Module14-Challenge_16544762101330/BikeSharing?:language=en-US&:display_count=n&:origin=viz_share_link)


**A. Starting and Destination Hubs and Gender Distribution:**
There were a total of 2,344,224 (~2.3M) bike rides and 146,752 bikes were used. It is apparent that there are some starting (Figure 1) and destination locations (Figure 2) that were popular. There were ~65.3% male, ~25.1% female and ~9.6% unknown (of gender records) bike riders (Figure 3) were among the users.  

![Starting hubs](/images/starting_hubs.png)

**Figure 1**. Starting bike ride hubs (locations). It shows that some starting locations are more popular than others.


![Destination hubs](/images/destination_hubs.png)

**Figure 2**. Starting bike ride hubs (locations). It shows that there are popular destinations (more or less similar to starting locations).


![Gender](/images/gender_breakdown.png)

**Figure 3**. Breakdown of trips by gender


**B. Length of time that bikes are checked out for all riders and genders**

The checked out trip duration is mostly within 1 hour (50 minutes). However, the most of the bike rides appears to be 5 or 6 minutes used by males (108,000 bikes) and females (~34,000 bikes), respectively. The peak checked out trip duration varied between 7-25 minutes for the others who did not have records on gender (~7000 bikes). Figure 4 shows the trip duration and Figure 5 indicated the trip duration by gender.   

![Checkout time](/images/checkout_time_for_users.png)

**Figure 4**. Trip duration for the bikes checked out  


![Checkout time by gender](/images/checkout_times_by_gender.png)

**Figure 5**. Trip duration for the bikes checked out (by gender)    


**C. Show the number of bike trips for all riders and genders for each hour of each day of the week**

The histogram (Figure 6) The peak usage time was between 6:00-9:00 AM for the morning and between  5:00-7:00 PM. Monday, Tuesday, and Thursday (and Friday to some extent) were the days where there was heavy usage of the bikes. It may be possible that the rides used bikes to go to work. However, people also used bikes on Saturday and Sunday (~7:00 AM - ~8:00 PM)  meaning that they may have used bike rides for other purposes as well. It should be noted that these riders might be tourists since these records are from August, which is a month in the Summer.

These trip days and times do not show a gender dependance (Figure 7). 

![Trips by user weekday by hour](/images/trips_by_week_day_by_hour.png)

**Figure 6**. Histrogram showing the number of bike trips during the day of the week  

![Trips by gender](/images/trips_by_gender.png)

**Figure 7**. Histrogram showing the number of bike trips by the day of the week and by the gender   


**D. Show the number of bike trips for each type of user and gender for each day of the week.**

When considering the user type, it is obvious that the subscribers are dominating in the bike rides (Figure 8). The mosed used day was Thursday followed by Friday, Tuesday, Monday, Saturday, Wednesday, and Sunday, in the decreasing order of the usage, respectively. 


![User trips by gender by weekday](/images/user_trips_by_gender_by_weekday.png)

**Figure 8**. Histogram showing the user trips by gender and day of the week


Additional analysis (below) shows that there are some starting locations (and destinations) that do not have subscribers (Figure 9).
- Packed Bubble chart (Figure 10) shows that there is some pattern for some bike riders based on their birth year and the user type. For example, those born on 1969 were the highest number of users of bikes and they were found to be non-subscribers. 


## ADDITIONAL VISUALIZATIONS


![Trips by user type](/images/trips_by_usertype.png)

**Figure 9**. Trips by user type at starting locations. Orange: Subscribers; Blue: Non-Subscribers.


![Trips by user type by birth year](/images/trips_by_usertype_by_birthyear.png)

**Figure 10**. Trips by user type (color) by birth year (year). Size of the circle depicts the number of rides used by users born on that particulr year.


## Summary: 

Provide a high-level summary of the results and two additional visualizations that you would perform with the given dataset.
We have visualized bike ride share information obtained from NY Citibike Ride Share program (August 2019). 

Our analysis shows that:
- There are top starting and destination (ending) locations (Hubs).
- There are more subscribers compared to non-subscribers (customers
- The peak day of ride share is Thursday (Thursday > Friday > Tuesday > Monday > Saturday > Wednesday > Sunday).
- The peak time of the usage is 6:00-9:00 AM IN the morning and 5:00-7:00 PM in the evening.
- There were no gender dependance on peak usage time or day

## Additional Analysis

- Some starting locations (and destinations) that do not have subscribers.
- Packed Bubble chart hows that there is some pattern for some bike riders based on their birth year and the user type.


**For initiating a new business in Des Moines, Iowa,** it is possible to get some insights from our analysis of the NY Citi Bike data.
For example, these are some suggestions for consideration:

1. Identify potential key starting and destination locations as hubs.
2. Introduce subscription service.
    - Discounts
    - Easier access to bikes, such as secure key etc.
3. For key locations, providing increased supply and increased repair services for bikes are essentially needed.
4. A system to replenish bicycles in the top starting destinations is needed as demand is increased.
    - e.g., moving cycles to stations with more demands from end locations (or other stations) by using trailers or truckds etc.). 
