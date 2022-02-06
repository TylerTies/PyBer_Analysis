# PyBer Analysis

## Project Overview
The CEO of PyBer has requested an analysis on their rideshare data.  For this analysis we were asked to create a multiple-line graph showing weekly fares for each city type.

The calculations required included:
1. Total Ride Count
2. Total Driver Count
3. Total Fares
4. Average Fare per Ride
5. Average Fare per Driver

These metrics were summarized by city type to understand the differences in the business and help guide future decisions at Pyber.

## Resources
- Data source: city_data.csv, ride_data.csv
- Software: Python 3.7.11, Jupyter notebook 6.4.6

## Ride Data Results
There is some important information presented in the overall summary by city type.  The differences can sometimes be sizable and may require changes.  Each metric is outlined below the chart.

![Data Summary](/analysis/PyBer_DF_summary.png)

- **Total Rides:** Urban cities make up the vast majority of PyBer's rides.  Urban accounts for more than Suburban and Rural combined.  This proves the importance of PyBer's urban presense and need to remain competitive in that market.
- **Total Drivers:**  The same trend can be seen for drivers as we had seen for Total Rides.  However, the data show that Urban cities have more Total Drivers than Total Rides.  Many drivers who signed up through PyBer in Urban cities never ended up giving a ride during the timeframe of the dataset.  Rural drivers saw the best ratio of rides to drivers.
- **Total Fares:** There were no surprises in the data when it came to total fares.  Urban cities once again dominiated the overall fares with a higher total than the other two city types combined.
- **Average Fare per Ride:** The data showed Rural having the highest average with almost $35 per ride while Urban was over $10 less per ride.  Suburban fell right in the middle of the two around $31.  This may be attributed to the average distance or time of the ride.  Urban rides may generally be shorter.
- **Average Fare per Driver:** This measure shows that on average Rural drivers saw the most success with $55.49 per driver over the timeframe.  Urban drivers only saw an average of $16.57 per driver during the same time.  Suburban drivers made roughly $40.  The average for urban drivers was brought down by the sizable number of drivers who didn't see any rides and made $0.

![Line Chart](/analysis/PyBer_fare_summary.png)

The chart above shows that total weekly fares were mostly consistent across the three city types with only minor fluctuations week-to-week.  It also clearly displays the portion of the service dominated by Urban business.  The urban business is important to the continued success of PyBer but there also may be opportunity in suburban and rural cities.

## PyBer Summary
The data made clear the importance of urban rides.  Efforts should be made to retain that business.  When examining the data we noticed that urban drivers may be finding it hard to even get riders.  It might be worthwhile to limit the amount of drivers or the number of rides per driver to ensure drivers aren't turned away from too much competition.  This would allow PyBer to build up a steady number of happy drivers instead of possibly having a few drivers drive the rest away.

Another opportunity might be to vary the pay of drivers depending on rider demand.  This would ensure drivers are available when riders are looking and help balance demand. This would also increase availablity of rural drivers by encouraging more drivers to join in these markets when driver count is low.  Riders in rural areas would benefit by having more consistency in driver availability.

One final recommendation might be to charge an additional fee for rides considered to be short distances.  These shorter rides can be time consuming driving to the pickup location and an additional fee might encourage urban drivers who feel like these rides aren't worth the trouble.  This would increase profitability for drivers in urban markets as long as the fee isn't too burdensome for riders.