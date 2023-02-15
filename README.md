# Walmart-sales-prediction
Predicting Walmart sales based on a specific store and specific departments.

The dataset used is retrieved from Kaggle and it contains weekly sales from 2011 to 2012.
The predictions created are *predictions of the next week for each week (i.e. date)* of the available dataset.
They are based on choosing a *specific Store* (specifically store 6) and *three departments* (specifically 5, 6 and 92), so that there is a variety on the size of the department (medium, small, large, accordingly).
There are notes for the convenience of the user, so that they can change the code to fit it as needed (choosing specific stores, departments, etc).
The model is based on **Arima** and **Facebook Prophet**.
As evaluation metrics, **MAPE**, **MPE**, **MAE** and **RMSE** are used.
