# Analysis of Uber and Lyft Rides in Boston

We are using the data for numerous Lyft and Uber rides in Boston and their prices (https://www.kaggle.com/brllrb/uber-and-lyft-dataset-boston-ma). The data was saved in `utility/data/rideshare_kaggle.csv`. Our goal is to use this dataset to gain some insight about characteristics of rides and _perhaps_ find some patterns in this data.

We followed an EDA process of understanding the data, wrangling the data, profiling the data, forming a hypothesis, investigating the hypothesis, summarizing results, and critically reviewing the workflow along with ethical questions. 

We used Numpy, Matplotlib, Seaborn, and Scipy to perform data analysis. 

We noticed that distance, surge multiplier, and ride type contribute to the difference in the distribution of prices in Uber and Lyft, while temperature does not. 
