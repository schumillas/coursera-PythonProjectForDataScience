# Python Project For Data Science

This repository contains the final project for the "Python Project For Data Science" course, one of the 10 courses in the "IBM Data Science Professional Certificate".

## Important remark

For the extraction of data using *yfinance.Ticker().history(period=)*, when trying to get the data using period="max", the following message raised: *(NameOfTheStock): No data found for this date range, symbol may be delisted*.
This happened for every stock. In order to retrieve any data and be able to progress forwards, I had to change the period to preiod="10y".

After doing a bit of research, I have discovered that there it seems to be an error in the base code of the yfinance package for when the period is set to "max". But I didn't want to get into trying to fix the base code.

Also important to notice that I have made this project in a local jupyter notebook.
