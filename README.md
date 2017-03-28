Pandas cookbook
===============

[pandas](http://pandas.pydata.org/) is a Python library for doing
data analysis. It's really fast and lets you do exploratory work
incredibly quickly.

The goal of this cookbook is to give you some concrete examples for
getting started with pandas. The [docs](http://pandas.pydata.org/pandas-docs/stable/)
are really comprehensive.

There are 3 data sets

* 311 calls in New York
* How many people were on Montréal's bike paths in 2012
* Montreal's weather for 2012, hourly

It comes with batteries (data) included, so you can try out all the
examples right away.

Table of Contents
=================


* A quick tour of the IPython Notebook
  <br> Shows off IPython's awesome tab completion and magic functions.
* 1: Reading from a CSV
  <br> Reading your data into pandas is pretty much the easiest thing. Even when the encoding is wrong!
* 2: Selecting data & finding the most common complaint type
  <br>It's not totally obvious how to select data from a pandas dataframe. Here I explain the basics (how to take slices and get columns)
* 3: Which borough has the most noise complaints? (or, more selecting data)
  <br>Here we get into serious slicing and dicing and learn how to filter dataframes in complicated ways, really fast.
* 4: Find out on which weekday people bike the most with groupby and aggregate
  <br> The groupby/aggregate is seriously my favorite thing about pandas and I use it all the time. You should probably read this.
* 5: Combining dataframes and scraping Canadian weather data
  <br>Here you get to find out if it's cold in Montreal in the winter (spoiler: yes). Web scraping with pandas is fun!
* 6: String operations! Which month was the snowiest?
  <br> Strings with pandas are great. It has all these vectorized string operations and they're the best. We will turn a bunch of strings containing "Snow" into vectors of numbers in a trice.
* 7: Cleaning up messy data
  <br> Cleaning up messy data is never a joy, but with pandas it's easier &lt;3
* 8: Parsing Unix timestamps
  <br> This is basically a quick trick that took me 2 days to figure out.
* 9 - Loading data from SQL databases
  <br> How to load data from an SQL database into Pandas, with examples using SQLite3, PostgreSQL, and MySQL.


TODO
====

* Joining dataframes
* Using stack/unstack
* ???
