# MLB-Starting-Pitcher-Factor-Analysis
This is a data science project where I created a multiple linear regression prediction model using LASSO and factor analysis methods, forecasting the MLB Free-Agent Starting Pitcher's upcoing year WAR and identifying the principal drivers of such WAR.

1) "1_1997_2017_Pitchers.xlsx": From 1997 to 2017, each year's pitcher records has been web-scrapped and merged into a dataset with total data of 15,995. Here, there are total of 24 variables related to the pitching performance.

2) "2_1997_2017_Starting_Pitchers_Transfers.xlsx": To use the personal information related variable "Trade_Ratio" and find pitchers who had experience of changing his team during pitcher's active time, I divided each player's number of transfers by cumulative active period. Such result is presented in the sheet "Transfers_And_Pitching".

3) "3_Pitching_Factor_Analysis.xlsx": The objective is to see how next season's performance will show up for the starting pitcher if that **pitcher changes his team**. Therefore, I narrowed the data pool only to the cases when the starting pitcher changed his team. With these conditions, the total data amount of the final dataset is 201.
