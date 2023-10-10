## Problem Statement
•	A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. 
•	The company wants to create robust business for the future market growth. They hired a consulting company to understand the factors on which the demand for these shared bikes depends.
•	The company want to know following facts about market:
•	Which variables are significant in predicting the demand for shared bikes.
•	How well those variables describe the bike demands


## Given Dataset
•	day.csv


## About the dataset
•	The given dataset has a data from year 2018 & 2019 of the bike renting business.
•	The Dataset has 730 rows and 16 columns.
•	The cnt variable is the target variable for the dataset.
•	Continuous Independent Variable: Temp, atemp, Humidity, Windspeed, Casual , Registered
•	Categorical variable: Season, Month, Weekday, Weathersit, Year, Holiday.


## Technologies Used
The following python libraries were used 
•	Pandas
•	Matplotlib
•	Seaborn
•	Sklearn
•	Statsmodel



## Conclusion from the dataset
We can see that the equation of our best fitted line is:

𝑐𝑛𝑡=0.3132+0.2380×𝑦𝑟+0.3635×𝑎𝑡𝑒𝑚𝑝−0.1339×𝑤𝑖𝑛𝑑𝑠𝑝𝑒𝑒𝑑−0.1290×𝑠𝑝𝑟𝑖𝑛𝑔+0.0685×𝑤𝑖𝑛𝑡𝑒𝑟−0.0733×𝑑𝑒𝑐−0.0568×𝑗𝑎𝑛−0.0829×𝑛𝑜𝑣−0.0419×𝑠𝑢𝑛−0.2706×𝑙𝑖𝑔ℎ𝑡𝑠𝑛𝑜𝑤−0.0785×𝑚𝑖𝑠𝑡𝑐𝑙𝑜𝑢𝑑𝑦
 
•	Most important factor affecting the business is temperature with a coefficient of 0.3635, for every change in temperature of 1 degrees demand increased by a factor of 0.3635 .
•	Second most important factor is year with coefficient value of 0.2380. Based on the historical data , given all internal and external remains unchanged , the company expected to see annual growth over  last year at around 23.8%.
•	The third most important factor  is windspeed with coefficient of -0.1339. This signifies that one unit increased in windspeed reduced the demand by 13.39%.

