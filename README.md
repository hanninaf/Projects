# Projects

The dataset contains observations of US domestic flights in 2013, and consists of the following fields:

Year: The year of the flight (all records are from 2013)<br>
Month: The month of the flight<br>
DayofMonth: The day of the month on which the flight departed<br>
DayOfWeek: The day of the week on which the flight departed - from 1 (Monday) to 7 (Sunday)<br>
Carrier: The two-letter abbreviation for the airline.<br>
OriginAirportID: A unique numeric identifier for the departure aiport<br>
OriginAirportName: The full name of the departure airport<br>
OriginCity: The departure airport city<br>
OriginState: The departure airport state<br>
DestAirportID: A unique numeric identifier for the destination aiport<br>
DestAirportName: The full name of the destination airport<br>
DestCity: The destination airport city<br>
DestState: The destination airport state<br>
CRSDepTime: The scheduled departure time<br>
DepDelay: The number of minutes departure was delayed (flight that left ahead of schedule have a negative value)<br>
DelDelay15: A binary indicator that departure was delayed by more than 15 minutes (and therefore considered "late")<br>
CRSArrTime: The scheduled arrival time<br>
ArrDelay: The number of minutes arrival was delayed (flight that arrived ahead of schedule have a negative value)<br>
ArrDelay15: A binary indicator that arrival was delayed by more than 15 minutes (and therefore considered "late")<br>
Cancelled: A binary indicator that the flight was cancelled<br>
Your challenge is to explore the flight data to analyze possible factors that affect delays in departure or arrival of a flight.<p>

Start by cleaning the data.<br>
Identify any null or missing data, and impute appropriate replacement values.<br>
Identify and eliminate any outliers in the DepDelay and ArrDelay columns.<br>
Explore the cleaned data.<br>
View summary statistics for the numeric fields in the dataset.<br>
Determine the distribution of the DepDelay and ArrDelay columns.<br>
Use statistics, aggregate functions, and visualizations to answer the following questions:<br>
What are the average (mean) departure and arrival delays?<br>
How do the carriers compare in terms of arrival delay performance?<br>
Are some days of the week more prone to arrival days than others?<br>
Which departure airport has the highest average departure delay?<br>
Do late* departures tend to result in longer arrival delays than on-time departures?*<br>
Which route (from origin airport to destination airport) has the most late* arrivals?*<br>
Which route has the highest average arrival delay?<br>
