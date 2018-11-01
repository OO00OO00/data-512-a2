# Bias in Data
Name: Will Frierson

Date: 2018-10-31

# Goal
The goal of this project is to illustrate bias of political articles within Wikipedia across different nations. In particular, a set of tables are produced that show the extremes of number of political articles per capita and proportion of high quality political articles for each country included in this analysis.

# Data sources used
To create these tables, we will draw from three data sources:
1) A dataset representing Wikipedia articles about politicians from many nations, produced by an R project found here: https://figshare.com/articles/Untitled_Item/5513449
2) A dataset representing population estimates for a set of nations found here: https://www.dropbox.com/s/5u7sy1xt7g0oi2c/WPDS_2018_data.csv?dl=0
3) Predicted Wikipedia article quality from the machine learning API ORES, discussed here: https://www.mediawiki.org/wiki/ORES

# Resources used
This analysis was prepared using Python 3.5 running in a Jupyter Notebook environment.
Documentation for Python can be found here: https://docs.python.org/3.5/
Documentation for Jupyter Notebook can be found here: http://jupyter-notebook.readthedocs.io/en/latest/

The following Python packages were used and their documentation can be found at the accompanying links:
requests, http://docs.python-requests.org/en/master/
json, https://docs.python.org/3/library/json.html
pandas, https://pandas.pydata.org/
os, https://docs.python.org/3/library/os.html
csv, https://docs.python.org/3/library/csv.html
numpy, http://www.numpy.org/
IPython, https://pypi.org/project/ipython/

# Files Created
This notebook creates 1 CSV file of data, named "wikipedia_political_article_bias_2018.csv", extracted and compiled as part of this analysis.

# License
This assignment code is released under the MIT license. For details, see the LICENSE.md file within this repo.

The Wikipedia political article dataset is made available via the CC-BY-SA 4.0 license. The population dataset from DropBox is made available per the sitewide terms of DropBox found here: https://www.dropbox.com/terms. The ORES API from Wikipedia is made available by the CC-BY-SA 3.0 license.
