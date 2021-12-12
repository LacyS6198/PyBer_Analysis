# Analysis Overview
The purpose of this project was to analyze the PyBer ride-sharing data to show the fares per city type from Janary - April 2019. The analysis included various metrics including:
- Total rides by city type
- Total drivers by city type
- Total fares by city type
- Average fare per ride
- Average fare per driver

Finally, the data was compiled to summarize each city type's metrics in a summary table, then further analyzed to chart the total fares by city type for the time period of January - April 2019.

# Results
Results are broken into two sections - **Results by City Type** and **Results by City Type and Date** . Details of these results are included within this section.

## Results by City Type
The calculated metrics were summarized to show the differences between city types as measured by Total Rides, Total Drivers, Total Fares, Average Fare per Ride, and Average Fare per Driver. 

![RideShare_Summary](https://user-images.githubusercontent.com/93630042/145716339-f37b3abe-fcbe-461c-bd6b-05198b90613d.png)

From the above chart we can see that the Urban cities have a significantly higher number of total drivers and rides completed, leading to an overall higher number of total fares. When looking at the average fare per-ride and per-driver we can see that the Urban city type actually has the lowest average for both measures. The Rural city type, while lowest in terms of total rides, drivers and fares, has the highest average fare per-ride and per-driver. The average fare per ride is $10.09 more in Rural areas than Urban. The average fare per driver is $38.92 higher in Rural areas than Urban. 

Assumptions can be made to help explain why the Urban city type has the lowest average fare amounts even though they have the highest totals. Assumptions can also be made to help explain why the Rural city type has the highest average fare amounts even thought they have the lowest totals. These assumptions include:
- Urban areas tend to have a dense population and many destination options for riders, leading to more rides. This in turn leads to more drivers and fares in total. 
- Urban areas tend to have a short distance between pick-up and drop-off locations.
- Rural areas tend to have a smaller population and fewer destination options for riders, leading to fewer rides. This in turn leads to fewer drivers and fares in total.
- Rural areas tend to have medium to long distances between pick-up and drop-off locations, resulting in higher fares per-ride. 
- Due to the lower demand and fewer drivers within Rural areas, this may result in a premium fare being paid as compared to Urban or Suburban areas.

## Results by City Type and Date
The below chart summarizes the total fares based on city type for the date range of 01/01/19 - 04/28/19.

![PyBer_fare_summary](https://user-images.githubusercontent.com/93630042/145716678-22fa9e38-756a-4cc0-8e3a-5207c5f48ae1.png)

Much of the above chart mirrors the **Results by City Type**, showing that the Urban has the highest total fares, Suburban has the second highest total fares, and finally Rural with this third highest total fares. 

Through the chart we can see trends within each city type from the months of January through April 2019. For the Urban and Suburban types, there is a peak towards the end of February. In the Rural areas, there is an increase during this time period as well (although not the highest time). 

Overall, there does not appear to be a consistent trend between the three city types when looking at week-over-week total fares. Each city type increases and decreases over the course of Jan - Apr at different times with no clear pattern between the three. This indicates that the demand for ride-sharing between the three city types is affected by different factors and each city type should be analyzed separately if trying to determine time-related trends and forecasting. 

#Summary
Through the analysis, the following was determined:

- Urban areas have the highest total fare, riders and drivers yet the lowest average fare per-rider and per-driver. 
- Rural areas have the lowest total fare, riders and drivers yet the highest average fare per-rider and per-driver.
- Suburban areas have lower totals than Urban areas and lower averages than the Rural areas. However, their data is closer to the Rural areas with significantly fewer total rides, drivers and fares than the Urban areas, and higher averages than the Urban areas. 
- Assumptions can be made to explain the differences between Urban, Rural, and Suburban areas. The totals and averages are likely affected by multiple factors including:
  - Population density
  - Number of rider destination options
  - Distance between pick-up and drop-off locations
  - Overall supply/demand factors potentially causing premiums to be applied to fares in certain areas
- No clear pattern between the three city types and time of year can be identified. 
- No clear pattern between each individual city type and time of year can be identified. Additional data would be requried to make meaningful conclusions, including multiple years and months.
