# Walmart Sales Data  
## Overview  

A project I started, but didn't fully finish, to determine the sales of Walmart stores. The dataset is from Kaggle called [Walmart Sales](https://www.kaggle.com/datasets/mikhail1681/walmart-sales) posted by user [Mikhail1681](https://www.kaggle.com/mikhail1681). I am not sure if this is real data or synthetic. The Kaggle data card does not say. I performed data validation and cleaning, used statistical analysis to check for data leakage, and began an analysis to treat it as a physical system. Ultimately, I wanted to draw up a partition function and treat each data point as a fermion that can transition across the partition if it has enough "energy". This would allow me to determine how each feature affected the "energy" of a Walmart store and inform managers how to get their store across the partition and become more profitable.  

## Tools Used:  
Python was the primary coding language.  

**Visualization:** Matplotlib and Seaborn  
**Data Storage/Structures:** Pandas and NumPy  
**Data Transformation, Analysis, and Feature Selection:** sklearn (pipeline, scoring metrics, transformers, scalers)  
**Models:** sklearn (KMeans, GaussianNB, HDBSCAN)  

## Methods:  
**Data Visualization:** I plotted the data using lineplots, barcharts, and heatmaps.  
**Exploratory Data Analysis:** I checked for missing data and outliers, transformed the dates into datetime formats, split the data into holiday vs non-holiday sets, then replotted to see how the holiday affects sales, and looked for data leakage in the features.  
**Model Selection:** I started using a random forest regressor and found that 94% of results were correctly classified. I decided not to tune the model because it may result in overfitting.  

## Results:  
I found that the random forest classifier was able to correctly predict the results for 94% of cases.
