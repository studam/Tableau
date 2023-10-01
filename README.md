# Tableau project - Citi Bike Analytics


## Background

![Citi-Bikes](Images/citi-bike-station-bikes.jpg)

As the new lead analyst for the [New York Citi Bike](https://en.wikipedia.org/wiki/Citi_Bike) Program, I am now responsible for overseeing the largest bike-sharing program in the United States. Expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have a number of questions about the program, so my first task on the job is to build a set of data reports to provide the answers.

## Tasks

**My task is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.** 

**To design visualizations for each discovered phenomenon. 

**The following are some questions to tackle. 

* How many trips have been recorded in total during the chosen period?

* By what percentage has total ridership grown?

* How has the proportion of short-term customers and annual subscribers changed?

* What are the peak hours in which bikes are used during the summer months?

* What are the peak hours in which bikes are used during winter months?

* Today, what are the top 10 stations in the city for starting a journey? 

* Today, what are the top 10 stations in the city for ending a journey? (Based on data, why?)

* Today, what are the bottom 10 stations in the city for starting a journey? (Based on data, why?)

* Today, what are the bottom 10 stations in the city for ending a journey (Based on data, why?)

* Today, what is the gender breakdown of active participants (Male vs. Female)?

* How effective has gender outreach been in increasing female ridership over the timespan?

* How does the average trip duration change by age?

* What is the average distance in miles that a bike is ridden?

* Which bikes (by ID) are most likely due for repair or inspection in the timespan?

* How variable is the utilization by bike ID?

**Next, as a chronic over-achiever:**

* Used my visualizations to design a dashboard for each phenomenon.
* The dashboards are accompanied by an analysis explaining why the phenomena may be occurring. 

**City officials would also like to see one of the following visualizations:**

A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey with zip code data overlaid on top.

A dynamic map that shows how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map.

* The map accompanied by a write-up unveiling any trends that were noticed during your analysis.



* Created a Tableau story that brings together the visualizations, requested maps, and dashboards.
  

## Considerations

The people reading the analysis will **NOT** be data analysts. My audience will be city officials, public administrators, and heads of New York City departments. My data and analysis need to be presented in a way that is focused, concise, easy-to-understand, and visually compelling. My visualizations are colorful enough to be included in press releases, and my analysis should be thoughtful enough to dictate programmatic changes. 

* Considered building my visualizations with small extracts of the data (i.e. single files) before attempting to import the whole thing. What I will find is that importing all 20+ million records of data will create performance issues quickly. 

* While utilizing all of the data may seem like a nice power play, I consider the time course in making my analysis. Is data from 2013 the most relevant for making bike replacement decisions today? Probably not. 

* Data alone doesn't "answer" anything. I will need to accompany my data visualizations with clear and directed answers and analysis.

* As is often the case, my clients are asking for a LOT of answers about their need-to-know and the importance of not "cramming in everything". Of course, I will answer each question but do so in a way that is organized and presentable.

* Since this is a project for the city, I needed to spend the appropriate time thinking through decisions on color schemes, fonts, and visual storytelling. The Citi Bike program has a clear visual footprint. As a suggestion, looked for ways to have my data visualizations match their aesthetic tones.

* Attention to labels. What exactly is "time duration"? What's the value of "age of birth"? I will almost certainly need calculated fields to get what I need.

* Keep a close eye on obvious outliers or false data. Not everyone who signs up for the program is answering honestly.

* In answering the question of "why" a phenomenon is occurring, I consider adding other pieces of information on socioeconomic or other geographic data. 

* Manipulated my data and played with settings in Tableau. Tableau is meant to be explored. 





