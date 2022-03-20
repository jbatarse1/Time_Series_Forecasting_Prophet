# Time_Series_Forecasting_Prophet

This Python application is to Forecast using Prophet. This program runs in Google Colab.

It uses timeframe manipulation and slicing methods to perform "Time Series" analysis; and uses a correlation to validate if any predictable relationship exists between Search Traffic trends and the Stock Volatility.

Also, Visualization techniques for time series data are created to better understand and predict search traffic and revenues.



## Technologies

This application incorportates the following required  dependancies to run:

### Import the required libraries and dependencies for Python


`import pandas as pd`

`import holoviews as hv`

`from fbprophet import Prophet`

`import hvplot.pandas`

`import datetime as dt`

`%matplotlib inline`



## Installation Guide

The following installation must be performed before running the program. It include:

### Install the required libraries in Colab.

`!pip install pystan`

`!pip install fbprophet`

`!pip install hvplot`

`!pip install holoviews`

## Usage

To run this application, create a clone on the local desktop. Then, initiate your conda environment and 
open file in Googel Colab at colab.research.google.com


Resources folder contains the following CSV files:

`google_hourly_search_trends.csv`

`mercado_dauily_revenue.csv`

`mercado_stock_price.csv`



These plots illustrate the data within the DataFrames. They include:

This line plot shows the trend of Average Search Traffic by the Day of the Week.

<img width="754" alt="Avg Traffic Day of Wk" src="https://user-images.githubusercontent.com/93550651/159183748-11cfd162-92be-4c5e-883e-2c2edbc7ff4c.png">


This line plot illustrates the daily spikes by hour of the day.

<img width="754" alt="May 2020 Search Traffic" src="https://user-images.githubusercontent.com/93550651/159183783-a1f5e5ec-200b-499b-9680-486e852f426a.png">


This plot graphs the Stock Price.

<img width="754" alt="Stock Price" src="https://user-images.githubusercontent.com/93550651/159183787-615de7ac-23b0-4ad4-8586-b0e4c3342fe5.png">


This plot graphs the Stock Volaility.

<img width="754" alt="Stock Volatility" src="https://user-images.githubusercontent.com/93550651/159183789-821b450d-6390-4705-987f-0b4c6667f63f.png">


Here are 4 plotted components that visualize the forecast results

<img width="640" alt="Components Fx" src="https://user-images.githubusercontent.com/93550651/159183797-d397dc06-3549-402c-901d-278091ad60dc.png">


Here is a Forecast plot.

<img width="769" alt="Forecast Plot" src="https://user-images.githubusercontent.com/93550651/159183802-ad6153d4-bbf0-456b-bea6-8cfb7ab34084.png">


This plot is the Prophet forecast for the trends data.

<img width="673" alt="Prophet Forecast" src="https://user-images.githubusercontent.com/93550651/159183807-b111af57-368c-4682-bb92-128a7c4be3fa.png">



## Contributors

Contributor: John Batarse  

Email: jbatarse@hotmail.com

LinkedIn: [Find me on LinkedIn](<https://www.linkedin.com/in/john-a-batarse-760a26116/>)


## License

Trilogy Education LLC. and UC Berkeley

