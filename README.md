Olympics Medal Prediction Project

Predicting Olympic Medal Counts using Linear Regression

Overview
Welcome to the Olympics Medal Prediction Project! In this project, we utilize machine learning techniques to forecast the number of medals countries can win in the Olympics. We've taken a dataset containing Olympic medal details, including country, year, athletes, age, previous medals, and current medals. The project is divided into several key steps:

Data Split: The dataset is divided into two parts - training and test. The training data consists of values up to the year 2012, while the test data contains values from the year 2013 onwards.

Linear Regression: We've applied Linear Regression, a powerful machine learning algorithm, to establish a relationship between athlete attributes (number of athletes, age, previous medals) and the number of medals won.

Evaluation: Our model's predictions are evaluated using mean absolute error (MAE) and error ratio metrics. This assessment is performed country-wise to gain insights into prediction accuracy.

Dataset
The dataset named "team.csv" includes information about Olympic medal counts, country-wise details, athlete attributes, and medal counts. The data is split into training and test sets based on the year of the event.
Results
Our model's performance is measured using the following metrics:

Mean Absolute Error (MAE): The average difference between predicted and actual medal counts.
Error Ratio: The percentage of predicted error compared to actual values.
These metrics offer valuable insights into the accuracy of our predictions.
It predicts the no of  medal won by a country by seeing the no of athlets in the country.
