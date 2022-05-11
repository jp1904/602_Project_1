# 602_Project_1


"Moving Violations Issued in March ### 2022".

Data contained in this layer pertains to moving citations issued by law enforcement of various DC agencies and federal partners. This dataset contains information on violations issued by various Agencies. These violations are classified by multiple categories of agencies and violations made by the public.

The Dimensions of the Dataset are 102927 rows and 29 columns.

Source of Dataset: https://opendata.dc.gov/datasets/DCGIS::moving-violations-issued-in-march-2022/explore

The notebook contains Exploratory Data Analysis on "Moving Violations Issued in March ### 2022".

Operations:

The Dataset has been analysed to understand the Data.
The null values are removed/ filled with required Data.
The unwanted columns are dropped as it may effec the result finally.
To represent the result the required plots and graphs are performed.
From the visuals, the conclusions such as "highest number of violations occured", "the reason for the ocuring more accidents from violation description" and etc.

Modelling:
Logistic Regression:
The method of modeling the probability of a discrete result given an input variable is known as logistic regression. The most frequent logistic regression models have a binary outcome, which might be true or false, yes or no, and so forth.

Results:
Train Data = 99.96%

Test Data = 99.80%

Roc curve score = 99.79%

Conclusions:
The violation named "Speed 11-15 MPH over the speed limit" has highest probability of Accident.
Agency named "MPD-SOD" has filed highest number of violations among all and top five agencies are displayed in the figure. 
As per the pie chart, it says the 92% of the values shows that probability of Accident is low.


Reference:
https://github.com/appliedecon/data602-lectures/

Further, it can also be analysed and applied with different machine learning algorithms more to retrieve the outcome more accurately.
