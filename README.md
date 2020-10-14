# Bike Rental Prediction
This project implements multiple linear regression to predict the number of bike rentals in Washington, D.C. based on environmental and seasonal factors.

The dataset I used can be found here: https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset

Click the "Open in Colab" button below to view this project in a Google Colaboratory notebook.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tatianabarbone/bike-rental-prediction/blob/master/bike_rental_prediction.ipynb)

## Conclusions and Results
This scatterplot shows the correlation between normalized temperature and bike rental count.
![scatterplot](https://github.com/tatianabarbone/bike-rental-prediction/blob/master/temp_count_scatter.png)

Using the regression coefficients, I found that windspeed has the strongest effect on the number of bike rentals, followed by temperature and humidity.

Based on the MAE, MSE, RMSE and the r<sup>2</sup> value , I concluded that my model did a decent job at predicting rental counts but could have been more accurate if I had more data, the data had a more linear relationship, or the features had a higher correlation to the label.
