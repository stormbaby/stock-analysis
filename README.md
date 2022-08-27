# stock-analysis
# An Analysis of a group of stock market tickers
Performing analysis on kickstarter data to uncover trends
---

Steve wants to do more research for his parents to include the entire stock market over the last few years. Here we will use the we used for a dozen stocks and build it out to work for thousands.  In the process I calculated how long it look expanding the original code, then refactored the code, making the time it processes less.
## Theater Outcomes using Launch Dates

Using excel I organized the theater outcomes and time of launch using pivot tables in excel. See image below.

![theater_outcomes_pivot](/theater_outcomes_pivot.png)

The data above shows that there were successful outcomes for all launch dates. I then created a line graph to show the trend.


![Theater_Outcomes_vs_Launch](/resources/Theater_Outcomes_vs_Launch.png)
The blue line, successful outcomes is higher for every launch month.  The failures line shows that there were less failures across the board.  The last line, canceled outcomes, is very few and even zero at times.

## Theater Outcomes using Goals

Using excel I organized the theater outcomes and goals using pivot tables in excel. See image below.

![VBA_Challenge_2017](/Resources_VBA/VBA_Challenge_2017.png)


The data above shows that there were successful outcomes for modest goals, up to 20,000. The percentages show that there were more successful campaigns than those that failed. The percentage of successful outcomes became unpredictable as the goals increased.  I then created a line graph to show the trend.

![Outcomes_vs_Goals](/resources/Outcomes_vs_Goals.png)

## Results

From the analysis I have arrived at two conclusions about the Theater Outcomes by Launch Date
   - The success of a theater's outcome overall didn't depend on the month of the launch.
   - Very few of the theater's outcomes failed.  

I concluded that if the goal was less than 20,000 there was a reasonable probably that the outcome would be successful.
  
Some limitations of this dataset would be
   - The Launch date used didn't include the year.
   - The data didn't show what the words successful and failed meant.  That data could have been broken up more to see gradients.

Another possible table and/or graph that we could create would be 
   -  A pie chart.  We could have the outcomes ( Successful, Failure etc) as pieces of the pie.
  






