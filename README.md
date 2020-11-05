# Terrorism-Analysis-Project
Building a Terrorism Analysis and Finding Insights Project

## About the data:
It is a real-time data compromising of more than 1.9 Lac rows in raw and unfiltered format.

The raw data was cleaned and divided in various csv files.

## Creating the User Interface

The data was cleaned using using python and its different libraries and creating a UI with table and graphical 
representation based on the based on combinations of Month, Day, Attack Type, Region, Country, State and City.

User is able to select any DAY and MONTH and based on the selections, incidents happened on that DAY and MONTH (maybe in any year ) are shown. 

A single visualization of every possible combination is created and updated accordingly.


Dash and its various components were used to create the UI.

```sh
import dash
import dash_html_components as html
from dash.dependencies import Input, Output
import dash_core_components as dcc
import dash_bootstrap_components as dbc
import dash_table as dt
```

And various tabs were created to show different graphs and data.



## Final Notes

What's in the files?

1. Main UI.py has the code to locally host the solution.


Thank You!


















