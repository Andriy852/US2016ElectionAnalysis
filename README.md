# Exploratory data analysis of 2016 US presidential elections
#### Author: Andrii Zhurba

This project analyzes the factors contributing to the Democratic Party's defeat in the election. The project includes data exploration, handling of missing values and outliers, as well as visualizing the results to uncover insights about the Democratic Party's performance.

**P.S.**: In this project, I adopted the role of an analyst working for the Democratic Party, and my explanations were presented from their perspective. However, it is important to clarify that this does not reflect personal support for the Democratic Party or any other political party in the United States.

The relevant project is located in src directory.
There are two notebooks in the project:
* Exploration_preparation.ipynb: Primarily focuses 
on the initial exploration of the data table, 
handling outliers, and addressing missing values.
* Exploration.ipynb: Concentrates on data visualization
and thorough exploration of the provided data. 
It aims to uncover the factors contributing to the 
Democratic party's defeat.

To investigate the causes behind the Democratic party's loss, I conducted 
an analysis focusing on the following aspects:
* I examined the total votes received by each party and conducted 
a comparative analysis. I pinpointed regions where our party 
received fewer and more votes compared to the Republicans.
* I analyzed the geographical distribution of victories for each candidate, 
identifying areas where Donald Trump had significant support and
where Hillary Clinton encountered notable challenges.
* I examined the geographical distribution of support for each candidate 
within each party. Specifically, I focused on understanding the areas of 
support for Donald Trump and analyze any variations. Similarly, I delved
into Hillary Clinton's areas of weakness.

## Source:

The data was downloaded on kaggle website: https://www.kaggle.com/datasets/benhamner/2016-us-election. 

To run the project's notebooks, install the following libraries:
```
pip install pandas numpy matplotlib seaborn geopandas sklearn
```