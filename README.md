# Analyzing-New-York-City-Taxi-Data
Big Bata : Analyzing the large dataset of New York City taxis, including data cleaning, preprocessing, enrichment, and feature engineering, such as enriching with GeoJSON data, to understand the behavior of taxis in New York City.

The main focus is on computing the taxi utilization, understanding the average time taken by taxis to find their next fare based on the drop-off borough, and analyzing the number of trips that start and end within the same borough or different boroughs.

The code is in a Jupiter Notebook [Python / Spark]. 

APACHE SPARK 
For the work, these benefits of using spark :
+ Efficient processing of the large NYC taxi dataset.
+ Ability to easily enrich the dataset with additional geospatial data.
+ Fast computation of metrics like utilization, average time to find the next fare, and trip categorization based on boroughs.
+ Scalability ensures that even if the dataset were much larger, the analysis could still be performed efficiently.
+ The use of user-defined functions (UDFs) and window functions in Spark made complex operations like calculating time differences between consecutive rows straightforward.

The analysis of the New York City Taxi dataset provided valuable insights into the operations of taxis in the city. The preprocessing and feature engineering steps ensured that the data was clean and enriched with relevant features, making the analysis more meaningful and accurate. The findings from this analysis can be used by taxi operators, city planners, and policymakers to make informed decisions and improve the efficiency of taxi services in New York City.
