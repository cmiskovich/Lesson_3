# Lesson_3


In this lesson I created a Jupyter notebook that reviews arbitrage opportunities in cryptocurrencies and specifically price differences on different marketpalces, in this example the Bitstamp and Coinbase marketplace.

First item was to create a GitHub repository and load the necessary files for the lesson along with creating a .gitignore file and then push the updates to GitHub.

Next I collected the data from the resources folder for Bitstamp and Coinbase using the Jupyter notebook.

Then I prepared the data for analysis by dropping the NaN or missing values in the dataframes.  Used the str_replace function to remove the "$" from the close column.  Converted the date type for the close column to float.  Finally reviewed the data in the Bitstamp and Coinbase data frame for duplicated values and dropped them.


After that I analyzed the data, first by using loc to select the timestamp and close columns from both files.  After that I used the describe function to get the summary statistics for each data frame.  Then we plotted both data frames separately and then I overlaid the two data frames in a plot. 

I then chose three dates one from each month to review for potential arbitrage earnings.  January 29th, February 2nd, and March 2nd, 2018. I plotted both marketplaces on each date along with creating the summary statistics and a box plot.

I calculated the arbitrage profits by measuring the spread and subtracting the lower priced marketplace from the higher one.  I then used a conditional statement  to generate summary statistics for each day's arbitrage spread.  I then calculated the spread returns for each date, generated a spread return that was greater than one percent this is to cover fees for the trades.  I then generated the summary statistics and plotted the results for each day.  I then calculated the potential arbitrage profits for each day and then the cumulative sum of the profits for each day.

Finally I created my analysis report using assumptions and trends that I made during the analysis, along with summary tables and visulaizations.
  
