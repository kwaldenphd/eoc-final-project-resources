# Elements of Computing: Tutorials

<a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" alt="Creative Commons License" /></a>
This tutorial was written by <a href="https://github.com/kwaldenphd">Katherine Walden</a> is licensed under a <a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

# Table of Contents

- [Data Wrangling](#data-wrangling)
  * [`Pandas`](#pandas)
  * [Web scraping](#web-scraping)
  * [Working with an API response](#working-with-an-api-resonse)
- [Visualization](#visualization)
  * [`matplotlib` basics](#matplotlib-basics)
  * [`pandas` plotting functions](#pandas-plotting-functions)
  * [`plotly` interactive visualization](#plotly-interactive-visualization)
- [Apps, widgets, and dashboards](#apps-widgets-and-dashboards)

[Click here](https://github.com/kwaldenphd/eoc-final-project-resources) to return to the landing page for this repository.

# Data Wrangling

## `Pandas`
- [Elements of Computing `Pandas` intro lab](https://github.com/kwaldenphd/pandas-intro)
- [Elements of Computing data wrangling in `Pandas` lab](https://github.com/kwaldenphd/eda-pandas)
- [`pandas` documentation](https://pandas.pydata.org/pandas-docs/stable/getting_started/intro_tutorials/)

## Web scraping
- [Elements of Computing web scraping lab (covers `beautifulsoup` and `pd.read_html()`](https://github.com/kwaldenphd/web-scraping-python)
- [`beautifulsoup` documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [`pd.read_html()` documentation](https://pandas.pydata.org/docs/reference/api/pandas.read_html.html)
- Eugenia Anello, "[An Intuitive Guide to Web Scraping Using Selenium](https://www.analyticsvidhya.com/blog/2021/08/an-intuitive-guide-to-web-scraping-using-selenium/)" *Analytics Vidhya* (8 August 2021)

## Working with an API response

Once you've gotten an API call working, one next step is figuring out what it might look like to get the API return (JSON data) into a Pandas DataFrame.

A couple ways to do that:
- [`pd.read_json()` documentation](https://pandas.pydata.org/docs/reference/api/pandas.read_json.html)
- [Adam Smith, "How to convert a JSON string to a pandas DataFrame in Python"](https://www.adamsmith.haus/python/answers/how-to-convert-a-json-string-to-a-pandas-dataframe-in-python)

But if the JSON is highly nested or hierarchical, mapping it onto a two dimensional table structure will lose some important structural dimensions of the data.

A couple places to start with nested JSON data (the short version is usually some flavor of Pandas' `json_normalize` function):
- Geeks for Geeks, "[Converting nested JSON structures to Pandas DataFrames](https://www.geeksforgeeks.org/converting-nested-json-structures-to-pandas-dataframes)" (22 November 2021)
- Derek Mortensen, "[Converting nested JSON structures to Pandas DataFrames](https://medium.com/swlh/converting-nested-json-structures-to-pandas-dataframes-e8106c59976e)" *The Startup* (10 May 2020)
- Jacob Boysen, "[Quick Tutorial: Flatten Nested JSON in Pandas](https://www.kaggle.com/code/jboysen/quick-tutorial-flatten-nested-json-in-pandas/notebook)" *Kaggle* (2017)

# Visualization

## `matplotlib` basics


## `pandas` plotting functions

## `seaborn` basics

## `plotly` interactive visualization

# Apps, widgets, and dashboards

# Getting started with statistical analysis and machine learning

With the exception of some of the `Seaborn` plot types explored at the end of the lab, most of the plots focus on methods for plotting summary statistics.

Python can support a wide variety of statistical analysis methods and modelling techniques.

`statsmodels` is a Python module that supports a variety of regression and linear models, time series analysis, survival and duration analysis, and multivariate statistics.
- [Statsmodels documentation](https://www.statsmodels.org/stable/user-guide.html)

`scikit-learn` is a machine learning Python library that supports a variety of classification algorithms (nearest neighbors, random forest, etc), regression models (nearest neighbors, random forest, etc), and clustering algorithms (k-Means, spectral, mean-shift, etc). 

`scikit-learn` incorporates/is built on `matplotlib` and has robust support for plotting and visualization.
- [Scikit-learn documentation](https://scikit-learn.org/stable/)

For a more holistic introduction to machine learning concept and workflows in Python:
  * [Prof. Walden's "Getting Started With Machine Learning in Python lab](https://github.com/kwaldenphd/machine-learning-intro/blob/main/ml-python-intro.md#machine-learning-libraries) 

# Return to Home
[Click here](https://github.com/kwaldenphd/eoc-final-project-resources) to return to the landing page for this repository.
