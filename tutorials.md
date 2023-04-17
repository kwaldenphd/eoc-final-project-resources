# Final Project: Tutorials (Elements of Computing II)

<a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" alt="Creative Commons License" /></a>
This tutorial was written by <a href="https://github.com/kwaldenphd">Katherine Walden</a> is licensed under a <a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

# Table of Contents

- [Data Wrangling](#data-wrangling)
  * [`Pandas`](#pandas)
  * [Web scraping](#web-scraping)
  * [Working with an API response](#working-with-an-api-response)
- [Visualization](#visualization)
  * [General](#general)
  * [`matplotlib` basics](#matplotlib-basics)
  * [`pandas` plotting functions](#pandas-plotting-functions)
  * [`seaborn` basics](#seaborn-basics)
  * [`plotly` interactive visualization](#plotly-interactive-visualization)
- [Jupyter Notebook outputs](#jupyter-notebook-outputs)
  * [Report](#report)
  * [Static notebook](#static-notebook)
  * [Interactive notebook](#interactive-notebook)
- [Widgets, apps, and dashboards](#widgets-apps-and-dashboards)
- [Other](#other)
  * [Statistical analysis and machine learning](#statistical-analysis-and-machine-learning)
  * [Sport data/analytics resources](#sport-dataanalytics-resources)

[Click here](https://github.com/kwaldenphd/eoc-final-project-resources) to return to the landing page for this repository.

# Data Wrangling

## `Pandas`
- [Elements of Computing `Pandas` intro lab](https://github.com/kwaldenphd/pandas-intro)
- [Elements of Computing data wrangling in `Pandas` lab](https://github.com/kwaldenphd/eda-pandas)
- Lisa Tagliaferri, "[How To Install the pandas Package and Work with Data Structures in Python 3](https://www.digitalocean.com/community/tutorials/how-to-install-the-pandas-package-and-work-with-data-structures-in-python-3)" *Digital Ocean* (10 February 2017)
- [`pandas` documentation](https://pandas.pydata.org/pandas-docs/stable/getting_started/intro_tutorials/)

## Web scraping
- [Elements of Computing web scraping lab (covers `beautifulsoup` and `pd.read_html()`](https://github.com/kwaldenphd/web-scraping-python)
- [`beautifulsoup` documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [`pd.read_html()` documentation](https://pandas.pydata.org/docs/reference/api/pandas.read_html.html)
- Eugenia Anello, "[An Intuitive Guide to Web Scraping Using Selenium](https://www.analyticsvidhya.com/blog/2021/08/an-intuitive-guide-to-web-scraping-using-selenium/)" *Analytics Vidhya* (8 August 2021)

## Working with an API response

Once you've gotten an API call working, one next step is figuring out what it might look like to get the API return (JSON data) into a Pandas DataFrame. It's useful to double-check the top-level keys in the API return to make sure you have a good sense of how the data is structured.

A couple ways to do that:
- [`pd.read_json()` documentation](https://pandas.pydata.org/docs/reference/api/pandas.read_json.html)
- [Adam Smith, "How to convert a JSON string to a pandas DataFrame in Python"](https://www.adamsmith.haus/python/answers/how-to-convert-a-json-string-to-a-pandas-dataframe-in-python)

But if the JSON is highly nested or hierarchical, mapping it onto a two dimensional table structure will lose some important structural dimensions of the data.

A couple places to start with nested JSON data (the short version is usually some flavor of Pandas' `json_normalize` function):
- Geeks for Geeks, "[Converting nested JSON structures to Pandas DataFrames](https://www.geeksforgeeks.org/converting-nested-json-structures-to-pandas-dataframes)" (22 November 2021)
- Derek Mortensen, "[Converting nested JSON structures to Pandas DataFrames](https://medium.com/swlh/converting-nested-json-structures-to-pandas-dataframes-e8106c59976e)" *The Startup* (10 May 2020)
- Jacob Boysen, "[Quick Tutorial: Flatten Nested JSON in Pandas](https://www.kaggle.com/code/jboysen/quick-tutorial-flatten-nested-json-in-pandas/notebook)" *Kaggle* (2017)

# Visualization

## General

### Towards Data Science
* [*Towards Data Science*](https://towardsdatascience.com/) (Medium blog)
  * [Posts tagged "Python"](https://towardsdatascience.com/tagged/python)

### The Python Graph Gallery
From [The Python Graph Gallery](https://python-graph-gallery.com/):
<blockquote>Welcome to the Python Graph Gallery, a collection of hundreds of charts made with Python. Charts are organized in about 40 sections and always come with their associated reproducible code. They are mostly made with Matplotlib and Seaborn but other library like Plotly are sometimes used.</blockquote>

## `matplotlib` basics
- ["Introduction to matplotlib" EoC lab](https://github.com/kwaldenphd/matplotlib-intro)
- Michelle Morales, "[How to Plot Data in Python 3 Using matplotlib](https://www.digitalocean.com/community/tutorials/how-to-plot-data-in-python-3-using-matplotlib)" *Digital Ocean* (7 November 2016)
- [`matplotlib` documentation](https://matplotlib.org/)
- [`matplotlib` gallery](https://matplotlib.org/stable/gallery/index.html)

## `pandas` plotting functions
- ["More with matplotlib" EoC lab](https://github.com/kwaldenphd/more-with-matplotlib)
  * [Jupyter Notebook with additional examples for plotting data in a Pandas `DataFrame`](https://colab.research.google.com/drive/17-y-UVg91w-nFxjg6oOY1zAK8dpf0KOa?usp=sharing)
- Lisa Tagliaferri, "[Data Analysis and Visualization with pandas and Jupyter Notebook in Python 3](https://www.digitalocean.com/community/tutorials/data-analysis-and-visualization-with-pandas-and-jupyter-notebook-in-python-3)" *Digital Ocean* (23 February 2017)
- [`pandas` plotting documentation](https://pandas.pydata.org/docs/user_guide/visualization.html)

## `seaborn` basics
- [`seaborn` section from the EoC "More with matplotlib" lab](https://github.com/kwaldenphd/more-with-matplotlib)
- [`seaborn` documentation](https://seaborn.pydata.org/)
- [`seaborn` gallery](https://seaborn.pydata.org/examples/index.html)

## `plotly` interactive visualization
- ["Interactive visualization" EoC lab](https://github.com/kwaldenphd/interactive-visualization-python)
- [`plotly` documentation](https://plotly.com/python/plotly-fundamentals/)
- [`plotly` gallery](https://plotly.com/python)

## Mapping
- [Static maps with `Pandas`, `GeoPandas`, and `Matplotlib`](https://github.com/kwaldenphd/more-with-matplotlib#mapping)
- [Interactive maps with `Pandas`, `GeoPandas`, `Plotly`, and `Shapely`](https://github.com/kwaldenphd/interactive-visualization-python#maps)

# Jupyter notebook outputs

There are various options for exporting or sharing a Jupyter Notebook. The "[Exporting the Jupyter Notebook](https://reproducible-science-curriculum.github.io/publication-RR-Jupyter/02-exporting_the_notebook/index.html)" from Data Carpentry's *[Sharing and Publishing Jupyter Notebooks](https://reproducible-science-curriculum.github.io/publication-RR-Jupyter/)* tutorial provides a good overview of these options.

See also: 
- Khelifi Ahmed Aziz, "[Learn How to Write Markdown and LaTeX in The Jupyter Notebook](https://towardsdatascience.com/write-markdown-latex-in-the-jupyter-notebook-10985edb91fd)" *Towards Data Science* (3 April 2020)
- Technical documentation for [`nbconvert`](https://github.com/jupyter/nbconvert).

## Report
- Kessie Zhang, "[How to Convert Jupyter Notebooks into PDFs](https://towardsdatascience.com/how-to-convert-jupyter-notebooks-into-pdf-5accaef3758)" *Towards Data Science* (20 August 2020)
- [Pandoc user guide](https://pandoc.org/MANUAL.html)

## Static notebook
- [GitHub](https://reproducible-science-curriculum.github.io/sharing-RR-Jupyter/01-sharing-github/)
  * [Uploading to GitHub from Google CoLab](https://www.geeksforgeeks.org/how-to-upload-project-on-github-from-google-colab/)

## Interactive notebook
- [Google CoLab](https://colab.research.google.com/)
- [NB Convert](https://nbviewer.org/)
- [Binder](https://mybinder.org/) 

## Widgets, apps, and dashboards

### Widget
- [`ipywidgets`](https://ipywidgets.readthedocs.io/en/latest/index.html)
- [`plotly`](https://plotly.com/python/#jupyter-widgets)

### App

Instructional resources for creating a `dash` app in Python:
  * Sample apps created by Prof. Walden
    * [ND Football Data](https://github.com/kwaldenphd/sample-dash-app)
    * [Baseball Reference Data](https://github.com/kwaldenphd/baseball-dash-sample)
  * [Running a `dash` app in a Jupyter Notebook using `JupyterDash`](https://medium.com/plotly/introducing-jupyterdash-811f1f57c02e)
  * [Overview](https://github.com/kwaldenphd/dash-python)
  * [Deploying via Heroku](https://github.com/austinlasseter/flying-dog-beers)

# Other

## Statistical analysis and machine learning

With the exception of some of the `Seaborn` plot types, most of the plot types covered in the course focus on methods for plotting summary statistics.

Python can support a wide variety of statistical analysis methods and modelling techniques.

`statsmodels` is a Python module that supports a variety of regression and linear models, time series analysis, survival and duration analysis, and multivariate statistics.
- [Statsmodels documentation](https://www.statsmodels.org/stable/user-guide.html)

`scikit-learn` is a machine learning Python library that supports a variety of classification algorithms (nearest neighbors, random forest, etc), regression models (nearest neighbors, random forest, etc), and clustering algorithms (k-Means, spectral, mean-shift, etc). 

`scikit-learn` incorporates/is built on `matplotlib` and has robust support for plotting and visualization.
- [Scikit-learn documentation](https://scikit-learn.org/stable/)

For a more holistic introduction to machine learning concept and workflows in Python:
  * [Prof. Walden's "Getting Started With Machine Learning in Python lab](https://github.com/kwaldenphd/machine-learning-intro/blob/main/ml-python-intro.md#machine-learning-libraries) 

## Sport data/analytics resources
A few other specialized resources that may be useful...
* FC Python, [*Learn Python and Data Science With Football*](https://fcpython.com/) (website with tutorials/resources for soccer/football data)
* Devin Pleuler, [*Soccer Analytics Handbook*](https://github.com/devinpleuler/analytics-handbook) (GitHub repository with tutorials/resources)
* [*Towards Data Science*](https://towardsdatascience.com/) (Medium blog)
  * [Posts tagged "Python"](https://towardsdatascience.com/tagged/python)
  * [Posts tagged “Sports”](https://towardsdatascience.com/tagged/sports) 
  * [Posts tagged “Sport Analytics”](https://towardsdatascience.com/tagged/sports-analytics) 
- Daniel Poston, "[Scikit-Learn Tutorial: Baseball Analytics](https://www.datacamp.com/community/tutorials/scikit-learn-tutorial-baseball-1)" *DataCamp* (4 May 2017)

# Return to Home
[Click here](https://github.com/kwaldenphd/eoc-final-project-resources) to return to the landing page for this repository.
