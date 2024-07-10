
![alt text](https://www.cityguideny.com/columnpic/ndnyc-taxi1.jpg)

# Project Overview and Purpose
This is a project from Google Advanced Data Analytics.

We aim to conduct a data analytics project for the New York City Taxi and Limousine Commission (TLC). New York City TLC is an agency responsible for licensing and regulating New York City's taxi cabs and for-hire vehicles. The agency needs to develop a regression model that helps estimate taxi fares before the ride, based on data that TLC has gathered.

The dataset was downloaded from **https://www.kaggle.com/datasets/raminhuseyn/new-york-city-taxi-and-limousine-project/data**

The dataset columns are:

**ID**: Trip identification number

**VendorID**: A code indicating the TPEP provider that provided the record.

**tpep_pickup_datetime**: The date and time when the meter was engaged.

**tpep_dropoff_datetime**: The date and time when the meter was disengaged.

**Passenger_count**:

The number of passengers in the vehicle.

This is a driver-entered value.

**Trip_distance**:

The elapsed trip distance in miles reported by the taximeter.

**PULocationID**:

TLC Taxi Zone in which the taximeter was engaged

**DOLocationID**:

TLC Taxi Zone in which the taximeter was disengaged

**RateCodeID**: The final rate code in effect at the end of the trip.

1= Standard rate

2=JFK

3=Newark

4=Nassau or Westchester

5=Negotiated fare

6=Group ride

**Store_and_fwd_flag**: This flag indicates whether the trip record was held in vehicle memory before being sent to the vendor, aka “store and forward,” because the vehicle did not have a connection to the server.

Y= store and forward trip

N= not a store and forward trip

**Payment_type**: A numeric code signifying how the passenger paid for the trip.

1= Credit card

2= Cash

3= No charge

4= Dispute

5= Unknown

6= Voided trip

**Fare_amount**: The time-and-distance fare calculated by the meter.

**Extra**: Miscellaneous extras and surcharges. Currently, this only includes the 
1 rush hour and overnight charges.

**MTA_tax:** $0.50 MTA tax that is automatically triggered based on the metered rate in use.

**Improvement_surcharge**: $0.30 improvement surcharge assessed trips at the flag drop. The improvement surcharge began being levied in 2015.

**Tip_amount**: Tip amount – This field is automatically populated for credit card tips. Cash tips are not included.

**Tolls_amount**: Total amount of all tolls paid in trip.

**Total_amount**: The total amount charged to passengers. Does not include cash tips.

## We aim to:

1. **Get information from the raw data**
   
   1.1 Compare the revenue of different days of the week and months of the year
   
   1.2 Compare the number of rides on different days of the week and months of the year
   
   1.3 Mean tip amount per number of passengers

2. **Conduct an A/B test** to check whether or not there's a relationship between total fare amount and payment type.

3. **Build linear regression models** to predict taxi fare amounts.

4. **Build machine learning models** (Random Forest, XGBoost) to predict if a customer will not leave a tip.
   
