# bikesharing
## Overview

The purpose of this analysis was to develop visualizations with Tableau in order to show data to NYC Citibike investors. The visualizations were designed to present a bikesharing investment opportunity in Des Moines.

[link to dashboard](https://public.tableau.com/views/NYCCitibikeDashboard/NYCCitibikeDashboard1?:language=en-US&:display_count=n&:origin=viz_share_link "link to dashboard")

----
## Results
### PART 1 "Changing the data type"

- Initially, the data provided for "tripduration" needed to be changed from integer into a date/time type format by using pandas and jupyter notebook, the code used was the following:

![Screenshot](https://github.com/chgallegos/bikesharing/blob/main/resources/data%20type%20change%201.png)
![Screenshot](https://github.com/chgallegos/bikesharing/blob/main/resources/data%20type%20change%202.png)

- With this new CSV file, the analysis in tableau can be performed.

### PART 2 "Telling the Story"

- The analysis of the data was told by the use of Tableau stories, the screenshots provided support the findings:

##### "Number of Trips"

- We begin by analyzing the number of trips for the month of August to use as a sample
![Screenshot](https://github.com/chgallegos/bikesharing/blob/main/resources/number%20of%20trips.png)

##### "Short term V/S Annual Subscribers"

- Next, we determine which of these customers are subscribers V/S single use customers. This separation will allow us to get a better idea of a target market in terms of how people are using the service.

![Screenshot](https://github.com/chgallegos/bikesharing/blob/main/resources/customer%20type%20(Subscriber).png)

![Screenshot](https://github.com/chgallegos/bikesharing/blob/main/resources/customer%20type%20(Customer).png)

- From here we can determine that substantial marketing efforts towards subscriptions type of deals would be ideal for this business.


##### "Top Starting and Ending Locations"

- A very important part of the analysis will be to see where to put the stations based on data providing starting and ending location frequenzy.

![Screenshot](https://github.com/chgallegos/bikesharing/blob/main/resources/Top%20starting%20locations.png)

![Screenshot](https://github.com/chgallegos/bikesharing/blob/main/resources/Top%20ending%20locations.png)

- We can conclude that the downtown area with most tourist traffic would be an appropriate lead as to where to look for locations.

##### "Checkout time for users and gender breakdown"

- Checkout times will provide us with an idea of how long each bike is used per user, with this data we can calculate the appropriate amount of bikes needed as to maintain sustainable levels of available bikes for our customers.

![Screenshot](https://github.com/chgallegos/bikesharing/blob/main/resources/checkout%20times.png)

- It is also appropriate to see the gender breakdown of this checkout time as we would want to know who our customers are.

![Screenshot](https://github.com/chgallegos/bikesharing/blob/main/resources/checkout%20times%20by%20gender.png)

##### "Trips by weekday and gender breakdown"

- The overall usage of the bikes will allow us to know which days have the most usage. It also will allow the operations team with fundamental coordinating information on when to provide maintenance to the bikes.

![Screenshot](https://github.com/chgallegos/bikesharing/blob/main/resources/trips%20by%20weekday.png)
![Screenshot](https://github.com/chgallegos/bikesharing/blob/main/resources/trips%20by%20weekday%20(gender%20breakdown).png)

##### "Bike Repair"

- Bike repairs will need to be scheduled based on the usage, giving priority to the most used bikes first. The following visualization allows for a visual representation of the bikes needing maintenance v/s the bikes with less usage. It will also be beneficial to know what times it will be most appropriate to perform the maintenance, for this a visualization providing times of usage (peak hours) is provided as well.

![Screenshot](https://github.com/chgallegos/bikesharing/blob/main/resources/bike%20repair.png)
![Screenshot](August peak hours)

##### "User Trips by Gender by Weekday"

-Lastly, a more in depth breakdown of customers and usage time and day that will give the investors a better idea of the target market and how the business would need to operate based on the customer needs.

![Screenshot](https://github.com/chgallegos/bikesharing/blob/main/resources/user%20trips%20by%20gender%20by%20weekday.png)

----
## Summary 

- The analysis performed for the month of August in New York has been thoroughly performed and provides the data that needs to be utilized for an analysis of this type. Knowing the target market, which type of product is being purchased, having the gender breakdown and operational estimates are all fundamental aspects needed to be studied before starting a new business or penetrating another region.

- I do believe that New York should not be the location used as a sample due to the nature of the city. It is a huge travel destination for tourists from across the globe and my apprehension is based on finding lower volumes in Des Moines as well as different possible different usage patterns and behaviors.

- With my previous concerns I would suggest to utilize a few more pieces of data/visualizations. The first one for a breakdown of the usertype and birthyear, as to get general idea of potential target market that could be consistent across the board. The second piece of analysis.

![Screenshot](usertype by birthday)
![Screenshot](user user by birthyear and gender)
