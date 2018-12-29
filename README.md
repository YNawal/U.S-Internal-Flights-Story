# U.S Internal Flights Story



# Summary
A delayed transportation service is a waste of time and money for the carrier and the traveler. In this study we discussed the problem of delayed domestic flights in the United States. According to RITA, there were almost 54 million internal flights from January 2010 to October 2018, 19.4 of them were delayed.

Link to the story: https://public.tableau.com/profile/nawal4368#!/vizhome/U_SFlightDelays/U_SFlightsStory?publish=yes


# Design

1.	First story point

In this point, I tried to show a very general findings to describe simply our data and to ask my main question: from where the flight delays came?
I found that the bar chart is the relevant choice for the variables that I presented. I leave a window of filtering by year and by season so that the reader can interact with the plot.

2.	Second story point

In this story point, I explored the distribution of the average flight delays as well the proportion of delayed flights. I used histogram since the variables are continuous.

3.	Third story point

Here, I have explored the number of arrived flights across years and seasons to present all models formed over the years and seasons. Line charts are used at this step because they are the best choice for a continuous variable (Year).

4.	Third story point

To reinforce our previous findings, I have explored in the third story point the delay causes as well as the minute average delay over years and seasons. Line charts are used here to track changes over Year (continuous variable) and Season. I have added average reference lines to facilitate the comparison process.

5.	Fifth / Sixth story points

I continued my investigation to arrive at the origin cause of the delayed flights this time by accusing the busiest airports once (5th story point) and the most important airlines another time (6th story point). To show the biggest/ busiest airport, I used the distribution of airports on the map and the color mark to encode the flight density. While the bar chart is used to present the flight density by carrier.  I used also the scatter plot to explore the relationship between flight density and delayed flight proportion/ average delay. I encoded the airport name/carrier name by the color mark (It was enough to covey my message if only they were encoded by the detail mark). 

6.	Seventh story point

In the 6th story point, I moved to verify if any relationship exists between late causes (one by one separately) and flight density at airport or in carriers. In this point I used the stacked bar to explore flight late causes for each airport/ carrier. I found it the best to present and compare data in one place. 

7.	Eighth/ninth story points

Because there is no data about why flights were cancelled and diverted, I tried in the two last story points to reveal some information about them, by exploring the relationship between flight density in carriers /at airports and the flight status (cancelled, diverted and on-time status). This was in the 8th point story. In 9th point story I have explored the relationship between the statuses mentioned above and the season. Scatter plots are used in 8th story point since are the best to observe any trend in data and line charts in 8th story point to track changes over time (Year and Season variables).


# Files Description
./data/24388006_102018_5622_airline_delay_causes.csv  the data set extracted from the bureau of transporation statistics 
./data/final_data.csv: the final data set used to create the visualization

# Resources
•	Bureau of transporation statistics ttps://www.transtats.bts.gov/OT_Delay/ot_delaycause1.asp?pn=1&periodfrom=24217%20&periodto=24226

