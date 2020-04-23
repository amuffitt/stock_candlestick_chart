# Background

Candlestick charts are a type of financial chart for tracking the price movement of stocks. They show the open, close, high, and low prices for each day and can show interesting patterns and trends over time that some financial analysts/traders may use to make trading decisions.  

I think candlestick charts are an effective way to visualize a stock's price over time, and I wanted to learn more about creating them in Python using a Plot.ly candlestick chart.  The main reference I used was a tutorial at https://towardsdatascience.com/python-stock-analysis-candlestick-chart-with-python-and-plotly-e619143642bb that is a very straightforward way of learning to create these charts.

Examples are shown calling a single stock symbol to create a chart, and I also created a way to show charts for all DOW Jones Industrial Avg stock candlestick charts at once, by creating a list and then looping through it to show each chart.

# Dataset

The article provided a great free financial dataset API continuously updated at  https://financialmodelingprep.com/api/v3/historical-price-full/{quote}?timeseries={days} (where quote is populated by the stock symbol and days with the desired number of days to show).   The Python JSON package is used to convert the returned JSON to work with in Python and ultimately converted to a dataframe containing the needed open, close, high, and low info for each stock to easily create the candlestick chart from.

# Uploaded Files

- Stock Candlestick Chart.ipynb - This Python notebook goes through retrieving the financial stock data, creating and manipulating the dataframe, and showing the Plot.ly candlestick chart functionality by creating charts based on individual stock symbol inputs as well as the entire list of the 30 Dow Jones Industrial stocks.

