# US House Price Analysis and Prediction 
### A project for data management course in UKM master's degree course (Assignment_1)

![image](https://github.com/user-attachments/assets/33f3d2ed-4ff0-4958-828a-a9c122ed9422)

The housing market plays a crucial role in the U.S. economy, influencing financial stability, consumer spending, and policy decisions. With dynamic shifts driven by economic trends, demographic changes, and interest rate fluctuations, understanding the factors that affect house prices is more important than ever. Data-driven approaches offer valuable insights into these complex patterns, enabling more informed decision-making for buyers, sellers, investors, and policymakers. This project aims to analyze historical housing data and develop predictive models to anticipate future trends in U.S. house prices. Through this analysis, we seek to uncover meaningful patterns and contribute to better housing market strategies and planning. The project covers several section below:

## Simple ETL Process
ETL process include cleaning, transforming, and loading process. For this particular dataset, it requires minimal cleaning, mainly for excluding missing data and unrelated columns; transformation is also not needed; loading involves loading the data into a partitioned table in Hive for better querying performance. 
The tools used are <b>Hive</b> to store the housing data from year 1963 to 2016, and is queried to <b>Jupyter Notebook</b> for data visualization.

## Data visualization and analysis
Data are mostly in terms of time series format, where line plot is mainly used. Pie chart is also used to compare proportions.  
For the analysis part, all plot is provided with findings, interpretations, and recommendations for different parties such as individual house buyers, real-estate agents, policymakers, and investors etc. 

## Model building
Several model such as Holt-Winter models, Vector Error Correction model (VECM), and Vector Autoregressive model (VAR) were built to prediction house demand in the months. The performance is compared with the baseline model using Naive prediction. Holt-Winter models turns out to be the best model, with some downsides that can be improved in the future.
