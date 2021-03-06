# Lesson_3
  
# Primary application file

Using Jupyter lab create a file to present to the VP of my department about arbitrage opportunites in cryptocurrencies.  In order to that I had to collect CSV data in a Jupyter notebook file. Then prepare the datasets for analysis by cleaning missing and erroneous data. Finally analyze the data at a high level through summary statistics and visualizations, and use this information to select areas for deeper analysis. 

---

## Technologies

The following Technologies were used to develop this program:

Python 
    Version 3.9.7

Terminal
    Version 2.12.5 (444)

Visual Studio Code
    Version: 1.66.2 (Universal)
    Commit: dfd34e8260c270da74b5c2d86d61aee4b6d56977
    Date: 2022-04-11T07:49:20.994Z
    Electron: 17.2.0
    Chromium: 98.0.4758.109
    Node.js: 16.13.0
    V8: 9.8.177.11-electron.0
    OS: Darwin x64 21.4.0
    
Jupyter Lab 
    Version 3.2.9

---

## General information about analysis.

Arbitrage opportunities existed by as the months progressed the two marketplaces Bitstamp and Coinbase started having more similiar close prices.  This reduced the opportunity in February and it disappeared in March.  January had incredible opportunity for returns especially January 29th,2018 with a potential cumulative profits of $148,647.30.   With arbitrage opportuinities when they occur they are quickly discovered and then disappear.


---

## Information about datasets

Bitstamp and Coinbase datasets were created using the csv files provided in the Resource folder.  The length of time similiar for both was from January 1st, 2018 to March 31st, 2018.  Using those datasets I was able to plot both of them in for their entirety and also overlap them.  After that we were asked to do an early month and a late month so I ovelapped them for January and March 2018.

After that I specified days and created the following datasets:

January 29th, 2018:

arbitrage_spread_early Subtracted the larger close price from a marketplace from the other.

spread_return_early took the arbitrage_spred_early greater than zero and divided by the lower closing marketplace.

profitable_trades_early took the spread_return dataset and looked for amounts greater than .01 to cover any transaction fees.

profit_per_trade_early took the amount of profitable_trades and multiplied the amount by the marketplace close.

profit_sum_early takes profit_per_trade and sums the amount.

cumulative_profit_early takes profit_per_trade and uses the cumsum function to determine cumulative sum of profits.

February 2nd, 2018:

arbitrage_spread_middle Subtracted the larger close price from a marketplace from the other.

spread_return_middle took the arbitrage_spred_middle greater than zero and divided by the lower closing marketplace.

profitable_trades_middle took the spread_return dataset and looked for amounts greater than .01 to cover any transaction fees.

profit_per_trade_middle took the amount of profitable_trades and multiplied the amount by the marketplace close.

profit_sum_middle takes profit_per_trade and sums the amount.

cumulative_profit_middle takes profit_per_trade and uses the cumsum function to determine cumulative sum of profits.


March 2nd, 2018:

arbitrage_spread_late Subtracted the larger close price from a marketplace from the other.

spread_return_late took the arbitrage_spred_late greater than zero and divided by the lower closing marketplace.

profitable_trades_late took the spread_return dataset and looked for amounts greater than .01 to cover any transaction fees.

profit_per_trade_late took the amount of profitable_trades and multiplied the amount by the marketplace close.

profit_sum_late takes profit_per_trade and sums the amount.

cumulative_profit_late takes profit_per_trade and uses the cumsum function to determine cumulative sum of profits.


---

## Libraties used in analysis

Pandas

Path

%matplotlib

---

## Contributors


**Chris Miskovich**

Contact Information:

Email: cmiskovich@verizon.net

[LinkedIn](https://www.linkedin.com/in/christopher-miskovich-9a61b0234/) 

---

## License

[MIT](/License.txt)
