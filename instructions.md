### Week 1 – 3 (October 17 – Nov 4)

## With this data question, we will:
* Get familiar with Jupyter Notebooks
* Learn to read a csv file into your local environment
* Explore individual variables and their relatedness to other variables in the dataset
* Experience with numpy, scipy, pandas, matplotlib, seaborn
* Create a GitHub account

### In-class practice 1:
1.	Download two CSV files:
a.	Net Migration (http://data.un.org/Data.aspx?d=WDI&f=Indicator_Code%3aSM.POP.NETM)
b.	Percentage of Individuals using the Internet http://data.un.org/Data.aspx?d=ITU&f=ind1Code%3aI99H

2.	Launch a Jupyter Notebook.

3.	Import the required packages as follows:
        **import pandas as pd**
        **import matplotlib as mpl**
        **import numpy as np**
        **import matplotlib.pyplot as plt**
4.	Use the *%matplotlib inline* command so that your plots show in the notebook.
5.	Using the pandas read_csv() function, read the two datasets into your notebook.
6.	Take a look at the data types and the first 6 rows for both datasets.
7.	Drop the footnotes data from both datasets.
8.	Change the columns for the Net Migration data frame to ‘Country’, ‘Year’, and ‘Net_Migration’.
9.	Change the columns for the Internet Users data frame to ‘Country’, ‘Year’, and ‘Internet_Users_Pct’.
10.	Merge the two data frames to one.
11.	Look at the first five rows of your new data frame to confirm it merged correctly.
12.	Look at the last five rows.
13.	Subset the combined data frame to keep only the data for 2002, 2007, and 2012.
14.	 Create three new data frames, one for 2002, one for 2007, and one for 2012.
15.	Which country had the highest percent of internet users in 2012? What was the percentage?
16.	Which country had the lowest percent of internet users in 2012? What was the percentage?
17.	Repeat for 2002 and 2007.
18.	Which country had the highest percent of internet users in 2012? What was the percentage?
19.	Which country had the highest net migration in 2012? What was the net migration?
20.	Which country had the lowest net migration in 2012? What was the net migration?
21.	Create some scatterplots:
a.	2002 Percent Using the Internet vs Net Migration
b.	2007 Percent Using the Internet vs Net Migration
c.	2012 Percent Using the Internet vs Net Migration
22.	Are there differences across years? What do the plots tell you about any relationship between these two variables? Enter your observations as a markdown cell.
23.	Look at the distribution of Net Migration values for 2012. Is it unimodal?
24.	Look at the distribution of Internet Use for 2012. Is it unimodal?
25.	What are the top 5 countries in terms of internet use in 2012?
26.	Create a data frame called top_5_internet from the combined data frame that has all three years for these 5 countries. You should have 15 rows.
27.	Create a seaborn FacetGrid to show the internet usage trend over time for these 5 countries.
28.	Repeat the steps (23-25) to look at the trend for 5 countries with the lowest 2012 internet usage.
29.	Do the same thing (top 5 for 2012 and bottom 5 for 2012) to look at 10-year trends in Net Migration.
30.	Is there anything surprising or unusual in any of these plots? Searching on the internet, can you find any possible explanations for unusual findings?
31.	Download another data set from the UN data (http://data.un.org/Explorer.aspx) to merge with your data and explore.
32.	Look through the bokeh gallery (https://bokeh.pydata.org/en/latest/docs/gallery.html#gallery) and if time allows create a bokeh visualization using the UN data.

### In class practice 2:
1.	Import stats from scipy like so:
        **from scipy import stats**
2.	Print the docstring for stats:
        **print(stats.__doc__)**
3.	Create a set of 500 randomly generated numbers called iq_scores.
4.	Using the example at the bottom of this webpage as a guide (https://docs.scipy.org/doc/numpy-1.13.0/reference/generated/numpy.random.normal.html), plot the distribution of your iq_scores.  Does it look normally distributed?



