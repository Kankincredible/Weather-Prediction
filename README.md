# Weather-Prediction


> This repository contains dataset and code for predicting sub-seasonal temperatures (temperatures over a two-week period) using machine learning algorithms. The project aims to predict weather patterns for different US locations, for a number of start dates for the two-week observation, as well as the forecasted temperature and precipitation from a number of weather forecast models. 

> Orginal data comes from [WiDS Datathon 2023](https://www.kaggle.com/competitions/widsdatathon2023)

The datasets included in this repository are:

- `train_data.csv`: the training dataset, where `contest-tmp2m-14d__tmp2m`, the arithmetic mean of the max and min observed temperature over the next 14 days for each location and start date, is provided

- `test_data.csv`: the test dataset, where we withhold the true value of `contest-tmp2m-14d__tmp2m` for each row.


To use this code, follow these steps:

Clone the repository to your local machine.


For more details on the implementation and methodology used in this project, please refer to the code comments and documentation.






