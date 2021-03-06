# PyBer_Analysis
[Deliverable 1](https://github.com/jzebker/PyBer_Analysis/blob/main/analysis/pyber_summary_df.png)

[Deliverable 2](https://github.com/jzebker/PyBer_Analysis/blob/main/analysis/Pyber_fare_summary.png)

## Overview
Using python and pandas, create a summary DataFrame of the ride-sharing data by city type **and** a multiple-line graph that shows the total weekly fares for each city type.  In addition, submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.
## Results
### Summary Table - PyBer by City Type (Early 2019)
|  | Total Rides | Total Drivers | Total Fares | Average Fares | Average Fare per Driver |
|------------:|--------------:|------------:|--------------:|------------------------:|--------:|
|       Rural |           125 |          78 |     $4,327.93 |                  $34.62 | $55.49 |
|    Suburban |           625 |         490 |    $19,356.33 |                  $30.97 | $39.50 |
|       Urban |         1,625 |       2,405 |    $39,854.38 |                  $24.53 | $16.57 |

(1) **Total Rides -** PyBer was most frequently used in **Urban** cities.  Almost 70% of total rides were in urban cities.

(2) **Total Drivers -** Over 80% of the drivers operated in **Urban** cities.  Only about 16% and about 3% were in suburban and rural cities respectively.

(3) **Total Fares -** Over 60% of the total fares during the time period observed were generated in **Urban** cities.  About 30% and about 7% were generated in suburban and rural cities respectively.

(4) **Average Fares -** The average fare per ride was lowest in **Urban** cities and highest in **Rural** cities.

(5) **Average Fare per Driver -**  The average fare per driver was much lower in **Urban** cities when compared to both **Rural** and **Suburban** cities.  It is less than half and less than a third of the average fare per driver in suburban and rural cities respectively.

### Weekly Fares by City Type (Early 2019)
<p align="center">
  <img src="https://user-images.githubusercontent.com/84994321/125866003-cabc100a-4735-40e9-9525-6b4cb3406388.png">
</p>

(6) **Total Weekly Fares -** Per the graph above, total weekly fares remained fairly constant throughout the time period observed.  They were consistently higher in **Urban** cities vs either rural or suburban cities.  The above graph does not contain data for the last week listed in the data because it was not a full week.

## Summary
Recommendations from the data:

(1)  In the absence of information regarding overall demand (or possible unfulfilled demand) or overhead, operations in urban cities should be expanded.  Most of the total fares generated have consistently been from urban cities so this is where the majority of efforts should be focused.

(2)  There are more total drivers than total rides in urban cities while this is not the case with either rural or suburban cities.  This directly affects the calculated average fare per driver and seems to identify a large percentage of drivers in urban cities that have never driven.  Further analysis is needed to figure out why this disparity exists since the given dataset does not link the ride with the driver that drove it.

(3)  This data can also aid in recruitment for new drivers or serve as insight for current drivers.  The average fare per driver is over three times higher in rural cities and over two times higher in suburban cities than in urban cities.  Looking at the weekly data, this was steadily the case for early 2019.
