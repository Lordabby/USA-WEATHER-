# USA-WEATHER-ANALYISIS
Weather is a very important factor that determines our day-to-day activities, what we do eat, wear and where to go. 
Because of its importance, I decided to explore the USA weather dataset to know more about the climatic changes solely for learning purposes.
It is a countrywide weather events dataset that includes 7.5 million events and covers 49 states of the United States. Examples of weather events are rain, snow, storm, and freezing conditions.
The data is collected from January 2016 to December 2021, using historical weather reports that were collected from 2,071 airport-based weather stations across the nation.  

# Acknowledgements 
Moosavi, Sobhan, Mohammad Hossein Samavatian, Arnab Nandi, Srinivasan Parthasarathy, and Rajiv Ramnath. “Short and Long-term Pattern Discovery Over Large-Scale Geo-Spatiotemporal Data.” 
In Proceedings of the 25th ACM SIGKDD International Conference on Knowledge Discovery &amp; Data Mining, ACM, 2019.

# Problem Obejctives
* Which climatic event occurred most between 2016-2022?
* What year has the highest recorded cases of weather events starting from Jan,2016-dec20221?
* Which months have the highest occurrence of weather cases?
* What is the average time(minute) it took each event to occur?
* Top 3 states in the USA with heightened heavy rainfall.
* Top 5 airports with high event record.

# Data Sourcing;
The data used for this project was obtained on Kaggle, check the link below; 
https://www.kaggle.com/datasets/sobhanmoosavi/us-weather-events

# Data Transformation
* Data formatting
* Data Trimming
* Addition of new column containing the difference in minutes between starttime and endime using datediff()
![Screenshot (74)](https://user-images.githubusercontent.com/107351159/188279295-a999320f-2f07-4b31-95e7-789eccea83b7.png)

# Data Visualization
The dataset was visualised using Power Bi software.

# Insights
* Which climatic event occurred most between 2016-2022?

The most occurring event recorded was rainfall with a total value of  4.4M (58.8%). 161.37K was heavy rainfall, 3.65M was light rainfall and 584.36k was moderate rainfall. 

* What year has the highest recorded cases of weather events starting from Jan,2016-dec20221?

The event records escalated in 2018 to the value of 1.33M which may be due to an increase in reports released by the airports. However, from the year 2019- 2021, there was a significant drop in events records which may be due to the Covid'19 breakout and its lockdown in 2020.

 * Which months have the highest occurrence of weather cases?

Most event types occurred in January, February and December while there was a low event record in November, June and July.

* What is the average time(minute) it took each event to occur?

The cold event often lasted for an average time of 419.45 minutes ( approximately 7 hours) whenever it occurs, while Hail occurred within an average time of 36.21 minutes whenever it occurs.

* Top 3 states in the USA with heightened heavy rainfall.

The highest Heavy rainfall event was recorded in Texas State (TX) with a value of 16,512, then Florida state (FL) with a value of 16,070 and North Carolina State (NC) with a value of 10,490.

* Top 5 airports with high event record.

The first five airports with high event records are: 
K3TH, KMLP, KHAF, KHYW, and KJNW respectively.

# Thanks :)
