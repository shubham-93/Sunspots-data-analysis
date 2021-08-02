# Sunspots-data-analysis
Exploratory data analysis of sunspot numbers (Kaggle dataset).

*Note: The pd.read_csv() function takes the argument "../input/sunspots/Sunspots.csv". This is how it should be if the notebook is run on Kaggle. The filepath must be changed if the notebook is run somewhere else.*

The code may also be found on my Kaggle account at https://www.kaggle.com/shubhammaheshwari1/sunspots-analysis.

We use **pandas, matplotlib, scipy and statsmodels** libraries to perform data cleaning, analysis and visualization of the Kaggle time series dataset on sunspot number observations from 1749 to 2021 available at https://www.kaggle.com/robervalt/sunspots. The data is shown to have many interesting features: multiple maxima and minima occuring at a periodic time period of around 11 years (the well-known solar cycle), a longer season of around 120 years, sharp maxima, flatter minima, asymmetry between rises and falls, and low sunspot number variation during periods of minima (and vice versa).
