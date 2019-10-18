# data-512-a2
Repository DATA512 A2 assignment

# Bias in data
Win Nawat Suvansinpan
10/17/2019

# Goal
The goal of this assignment is to look at Wikipedia articles on political figures from different countries while focusing on the bias within data. This is done by measuring the coverage and quality of Wikipedia articles on politicians across different countries.

[Course wiki](https://wiki.communitydata.science/Human_Centered_Data_Science_(Fall_2019)/Assignments#A2:_Bias_in_data)

The quality aspect of the articles are given by [ORES](https://www.mediawiki.org/wiki/ORES) ("Objective Revision Evaluation Service") which predicts the quality of an article at a particular point in time through machine learning.

Coverage is defined by the number of politician articles per country population.

# Data sources
Data used in this exercise are:
- Politicians by Country from the English-language Wikipedia
  - Data on most English-language Wikipedia articles within the category "Category:Politicians by nationality" and subcategories, along with the code used to generate that data.
  - https://figshare.com/articles/Untitled_Item/5513449
- Population data
  - Data on population size of countries in the world as of mid-2018
  - https://www.prb.org/international/indicator/population/table/- 

# Resources
This analysis was prepared using Python 3.5 running in a Jupyter Notebook environment.
Documentation for Python can be found here: https://docs.python.org/3.5/
Documentation for Jupyter Notebook can be found here: http://jupyter-notebook.readthedocs.io/en/latest/

The following Python packages were used and their documentation can be found at the accompanying links
- [json]()
- [pandas]()
- [requests]()

# Files created
- `predictions.csv`
  - Generated from the results of API calls appended together to obtain the prediction data for Wikipedia articles used in this exercise.
- `wp_wpds_countries-no_match.csv`
  - A table containing countries with no matching article and population data.
- `wp_wpds_politicians_by_country.csv`
  - A table containing the article name, country, revision_id, article quality, and the country's population.

# Visualizations

# License
This assignment code is released under MIT license
