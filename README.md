# GUI-Application-to-Get-Live-Stock-Price

The stock price is the highest amount someone is willing to pay for the stock.

### I am going to write code for getting live share prices for each company and bind with GUI Application.


## Module Needed 

##### Yahoo_fin:

This module is used to scrape historical stock price data, as well as to provide current information on market caps, dividend yields, and which stocks comprise the major exchanges. To install this module type the below command in the terminal.

pip install yahoo_fin

Let’s write code to get stock data.

Import the yahoo_fin module.

from yahoo_fin import stock_info


Use stock_info.get_live_price() method to get live stock price.

## EX: stock_info.get_live_price("AMZN")

### Output

3198.93994140625


# Note 

please visit this site to get company Symbol like Amazon is AMZN, Reliance is RELFF.



