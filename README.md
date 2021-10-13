## CX1115 Mini Project: Stock Price Prediction

#### Description:
- Our project aims to predict the long-term trend of future stock prices based on the health of the company. 
- For the scope of the project, we decided to focus on Apple as the target company and implemented methods to predict their future trends.

#### Data Extraction:
- Our data was extracted from various repositories, which included Alpha Vantage (https://www.alphavantage.co/), Apple's Balance and Income sheets and US Federal Funds.

#### ML Model:
- Our stock price prediction model was primarily a multi-variate linear regression model with feature scaling for data manipulation to improve the performance of our model. 
- We used various performance measures to evaluate the performance of our model, such as Explained Variance (R^2), Adjusted Explained Variance (R^2) and Root Mean Squared Error (RMSE).

#### Results:
- Our model achieved a R^2 value of ~96% and RMSE value of ~13% on the train set and R^2 value of ~81% and RMSE value of ~18% on the test set, which is relatively well performing for a linear regression model on a complex problem of stock price prediction.
- We recognise the existance of more complex and potentially better performing models like LSTMs and ARIMA, but due to time constraints and the scope of the module, a linear regression model was concluded to be the best model for our project purposes.

----------------------------------------------------------------------------

*Please refer to the "Merged" folder for final submission files and codes.*
