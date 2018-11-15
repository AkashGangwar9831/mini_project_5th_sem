# mini_project_5th_sem

Visualisation is done through ‘subplots’ in python.
‘Matplotlib’ library with ‘pyplot’ module is used for representation of subplots.
‘Alpha_vantage’ api is used from fetching real time data from internet.
‘Alpha_vantage’ uses ‘TimeSeries’ module which takes argument as key (for fetching data from alpha_vantage) and ‘out_format’ that is ‘pandas’. 
‘get_intraday’ function is used for fetching data  for particular company as ‘symbol’(msft,appl,googl etc), and other arguments like ‘interval’ and ‘output size’.
Then I have ‘iloc’ function to get the closed stock column in a dataframe.
I have used ‘fix_yahoo_finance’ api which uses ‘pandas_datareader’ library for fetching historical price of two companies.
