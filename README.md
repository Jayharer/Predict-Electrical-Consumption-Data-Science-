# Predict-Electrical-Consumption-Data-Science-
Data science project

Problem Statement
Company of Electrolysia supplies electricity to the city. It is looking to optimise its electricity production based on the historical electricity consumption of the people of Electrovania. 
 
The company has hired you as a Data Scientist to investigate the past consumption and the weather information to come up with a model that catches the trend as accurate as possible. You have to bear in mind that there are many factors that affect electricity consumption and not all can be measured. Electrolysia has provided you this data on hourly data spanning five years. 
 
the training set is comprised of the first 23 days of each month and the test set is the 24th to the end of the month, where the public leaderboard is based on the first two days of test, whereas the private leaderboard considers the rest of the days. Your task is to predict the electricity consumption on hourly basis.


Note that you cannot use future information to model past consumption. For example, you cannot use February 2017 data to predict last week of January 2017 information.



The Evaluation criteria for this problem is RMSE.

Data --
Column Name     	               Description
ID	                             Unique ID
datetime	                       Datetime of record
temperature     	               Temperature at that hour
var1	                           Anonymized feature var1
pressure	                       Pressure at that hour
windspeed	                       Wind Speed at that hour
var2	                           Anonymized feature var2
electricity_consumption	(target) Electrical consumption (in MWh)
