# stock-analysis
# An Analysis of a group of stock market tickers
Performing analysis on stock ticker data to look at difference between 2017 and 2018 data. Refactor the underlying code to make the process quicker.
---

Steve wants to do more research for his parents to include the entire stock market over the last few years. Here we will use the we used for a dozen stocks and build it out to work for thousands.  In the process I calculated how long it look expanding the original code, then refactored the code, making the time it processes less.
## Comparing 2017 stock results vs 2018 results

For the year 2017, using VBA I added the total volume for each ticker, for each day. In addition, to find the returns for each ticket, I found the initial open ticker price and then the closing price to then calculate the annual return per ticker.  I completed the same analysis for 2018.  See images below.
### 2017
![Screen.Shot.2017](/Resources_VBA/Screen.Shot.2017.png)


### 2018
![Screen.Shot.2018](/Resources_VBA/Screen.Shot.2018.png)

In the charts it shows that there were many tickers with positive returns in 2017 ( colored in green).  In 2018 most tickers had negative returns ( colored in red).

### Execution times

Also shown in the charts above are the execution times for each years calculations.  The times were calculated by starting the timer at the beginning of the code, then stopped as the code ended.

## Refactoring the code

### 2017
![Screen.Shot.2017.Refactored](/Resources_VBA/Screen.Shot.2017.Refactored.png)


 ### 2018

![Screen.Shot.2018.Refactored](/Resources_VBA/Screen.Shot.2018.Refactored.png)

The refactoring of the code used arrays to capture the data as it ran through each line of the data, rather than running through all rows to capture data data for each ticker.  the Capturing of data this way saved almost half the time as shown in the message of the running time.  The underlying calculations after refactoring is seen to be the same.

## Summary

Refactoring has advantages and disadvantages
### Advantages
    - If the purpose of the code is time sensitive, refactoring is necessary to make the time it takes to execute the code as quick as possible
### Disadvantages
    - Refactoring can be quite time consuming. Writing code without a time constraint can be done more quickly, without a lot of reworking of the code to make small changes in the time.
    
I concluded that if the goal was less than 20,000 there was a reasonable probably that the outcome would be successful.
  
Some limitations of this dataset would be
   - The Launch date used didn't include the year.
   - The data didn't show what the words successful and failed meant.  That data could have been broken up more to see gradients.

Another possible table and/or graph that we could create would be 
   -  A pie chart.  We could have the outcomes ( Successful, Failure etc) as pieces of the pie.
  






