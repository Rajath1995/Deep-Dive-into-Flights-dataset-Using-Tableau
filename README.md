# Deep-Dive-into-Flights-dataset-Using-Tableau

Data Visualization of Flight delays with Tableau – Project 1 -Udacity.

  

Flight delays are one of the most common things in airline domain. The reasons could me many, few of the common reasons for delays are :
1.	Late aircraft arrangement.
2.	Airline delays due to staff issues.
3.	Air system delay.
4.	Departure delay due to air traffic control, aircraft check.
5.	Security issues.
Commercial airline defines delay as the period of time which flight is late or postponed. The delay is the difference between scheduled time and real time of departure or arrival.
Delays in flights causes many issues, mainly connecting flights could be missed for the passengers and which in turn might cause problems to the appointments of the passengers.
This project aims to get the insight on the flights data published by Kaggle https://www.kaggle.com/usdot/flight-delays/data.  A deep dive into flight data to understand which airline, destination, airports are delayed mostly and what all the reasons for the delay.
The following questions will be answered by the end of this report:
1.	What causes the flight delays mostly? And what is the average time for this delay?
2.	Which month of the year the airline industry sees the delays?
3.	Which airline performed poorly in terms of arrival time delay?
4.	Average departure delay for each airline with respect to the destination?
5.	Which airport in United states had the greatest number of flights delayed?
The flights dataset has 3 csv files:
1.	Airlines.csv
2.	Airports.csv
3.	Flights.csv
This particular project utilizes all the 3 datasets connected to one another (Inner join is implemented to connect each other)
The results from the analysis are :
1.	What causes the flight delays mostly? And what is the average time for this delay?

https://public.tableau.com/profile/rajath.nag.nagaraj#!/vizhome/Whatcausesflightdelay/Sheet3?publish=yes

The above visualization indicates clearly that late aircraft delay is the main reason for most of the flights to get delayed. This delay causes an average of 23.74mins and this is main reason for flight delays. The next reason behind the delays are airline delay which on average delays the flight by 18mins.

2.	Which month of the year the airline industry sees the delays?

https://public.tableau.com/profile/rajath.nag.nagaraj#!/vizhome/Whichmonthhadmostflightdelays/Sheet4?publish=yes

The month of June is the worst time to travel because it is seen that most of the flights are getting late during this month. The average departure delays during the month  was around 15mins.
The month of September was found to be the best time to travel around in the flights as the average departure delay was least among the rest of the year.

3.	Which airline performed poorly in terms of arrival time delay?

https://public.tableau.com/profile/rajath.nag.nagaraj#!/vizhome/AveragearrivaldelayforanAirline/Sheet2?publish=yes

It is found that Spirit airline has average arrival delay of 15.73mins which is highest among all other airlines, Alaska airlines on the other hand was pretty time efficient they had negative arrival time average indicating that they reached prior to scheduled arrival time.

4.	Average departure delay for each airline with respect to the destination?
https://public.tableau.com/profile/rajath.nag.nagaraj#!/vizhome/Averagedeparturedelaytimebyanairline/Sheet1?publish=yes

It is found that United airlines had 167minutes average departure delay to Fairbanks destination making it one of the highest delayed airlines to Fairbanks location.  On the other hand, Delta airlines travelling to Atlanta was delayed 260 times totally.

5.	Which airport in United states had the greatest number of flights delayed?
https://public.tableau.com/profile/rajath.nag.nagaraj#!/vizhome/Flight-delaysanalysis/Sheet6

It is observed that Hartsfield Jackson Atlanta International Airport had a total of 17,641 flights arrived late in total making it to a destination in which the likelihood of a flight getting late highest. 
Overall findings from the data:
https://public.tableau.com/profile/rajath.nag.nagaraj#!/vizhome/Flight-delaysanalysisdashboard/Dashboard1

Conclusion: The flight delays are very important factor for aircrafts operators, ticket cost to customers and most importantly the customer base of an airline might be affected if the service is not effective.


