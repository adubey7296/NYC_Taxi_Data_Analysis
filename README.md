# NYC_Taxi_Data_Analysis

## Sequence-- Table --> Queries --> QueriesA --> Analysis1 --> Analysis2

# Problem Statement:

The New York City Taxi & Limousine Commission (TLC) has provided a data of trips made by the taxis in the New York city. The detailed trip-level data is more than just a vast list of taxi pickup and drop off coordinates.

The records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations (location coordinates of the starting and ending points), trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts etc.

By aggregating the aforementioned records this dataset was created that provides precise location coordinates for where the trip started and ended, timestamps for when the trip started and ended, plus a few other variables including fare amount, payment method, and distance travelled.

# Link to downlaod the dataset:

https://s3.amazonaws.com/nyc-tlc/trip+data/yellow_tripdata_2017-11.csv

https://s3.amazonaws.com/nyc-tlc/trip+data/yellow_tripdata_2017-12.csv

# Basic Data Quality Checks:

1.How many records has each TPEP provider provided?

2.Checked whether the data is consistent (shoulde be for November and December month) and identified the data quality issues.

3.Identified the erroneous rows in the dataset (and also which vendor has provided those records).

# Analysis-I

1.Compared the average fare for November and December.

2.Explored the ‘number of passengers per trip’ i.e. how many trips are made by each level of ‘Passenger_count’?

3.Found out the most preferred mode of payment.

4.Found out the average tip paid. Compared the average tip with the 25th, 50th and 75th percentiles.

5.Explored the ‘Extra’ (charge) variable i.e. what is the fraction of total trips where an extra charge is levied?
# Analysis-II

1.Correlation between the number of passengers and tip paid.

2.Created five buckets of ‘tip paid’: (0-5), (5-10), (10-15), (15-20) and >=20. Calculated the percentage share of each bucket (i.e. the fraction of trips falling in each bucket).

3.Found out the month has a greater average ‘speed’ among November and December.

4.Analyzed the average speed of the most happening days of the year i.e. 31st December (New year’s eve) and 25th December (Christmas Eve) and compared it with the overall average.
