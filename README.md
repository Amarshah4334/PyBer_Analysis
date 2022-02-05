# PyBer_Analysis
Working on PyBer with Matplotlib
PyBer_Analysis
Project Overview
Analyze and visualize PyBer 2019 ride-sharing data using Python, Pandas and Matplotlib, to help the company improve access to ride-sharing services and determine affordability for underserved neighborhoods.
The analysis is based on the following points among the different city types:

the percentage of total rides,
the percentage of total drivers,
the percentage of total fares,
the average fare per ride and driver,
the total fare by city type.
Resources
Data Source: city_data.csv, ride_data.csv
Software: Python 3.7.7, Anaconda Navigator 1.9.12, Conda 4.8.4, Jupyter Notebook 6.0.3
Results
The percentage of total rides by city type


More than 2/3 of the total rides in 2019 were realized in urban cities. Suburban areas count for over 26% of the total rides and rural cities have the smallest proportion with only for 5.3%.

The percentage of total drivers by city type


Urban cities drivers were by far in majority with 80.9% of the company's drivers force in 2019. Surbuban and rural drivers were respectively 26.3% and 5.3% of the total drivers in 2019.

We notice the very small proportion of drivers in rural areas.

The percentage of total fares by city type


Here again we notice the influence of urban areas in the company's business model. Close to 63% of the 2019 total fares was realized in urban cities. Surbuban activity counted for about 31% and the smallest proportion was in rural neighborhoods.

The average fare per ride and driver by city type
The following bubble chart shows the relationship between the average fare price and the number of rides and drivers categorized by the different city types.



We notice that the average fare tends to decrease as the total number of rides per city increases. This is a negative relationship.
As per the driver count per city, it appears that the bubbles get larger when the average fare decreases and/or when the total number of rides increases.
Rural areas have the least number of drivers and rides per city and its fare ranges from high to middle prices. It is difficult to see the relation between those parameters. Other inputs like population size, ride distances, and cellphone coverage would be interesting to analyze to determine any correlation.

The total fare by city type
The following line chart shows the total fare by city type from January to April 2019.



The urban weekly total fare is around 9 and 2.25 times higher than rural and surburban ones respectively.

Summary
In the most underserved neighborhoods, PyBer ride-sharing services would not be the first option for travels as the fares are pretty high.
The correlation between the drivers force, the number of rides and the average fare price is not clear so additional analysis including geographic size, travel distances, cellphone coverage would be needed to get a clearer picture.
Suburban drivers were only about 17% of the total drivers but accounted for more than 30% of the total fares and just above a quarter of the rides.
Improving access to PyBer service in those areas will imply finding the right balance between incentives for more riders to join in and the right fare charge that will motivates riders to pick PyBer app as the first choice for their travels.
Additional analysis including geographic size, population and social conditions, travel distances would be interesting to dive in.
The general tendencies is high number of drivers and rides goes with medium to low fare.
On the scatter plot, we notice some urban cities with low number of drivers and low average fare but pretty high count of rides. Analyzing the average number of drivers against the population and infrastructure and economic activity in those cities would help understand those disparities.
