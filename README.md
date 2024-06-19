# S&P 500 Stock Price Prediction Using Gaussian Mixture Models
<br>
This project utilizes Gaussian Mixture Models (GMM) to predict the closing prices of S&P 500 stocks for the next 14 days. The methodology follows the approach described in the paper "Hidden Markov Models for Stock Market Prediction."

## Dataset: 
The dataset used is the historical daily prices of the S&P 500 index, including:
<br>
Open price, High price, Low price, Close price, Adjusted close price, Volume
<br>
## Methodology: 
The approach involves calculating Fractional Changes: Fractional changes for fracChange, fracHigh, and fracLow are computed.
Discretization: Continuous observations are discretized into a specified number of bins.
Training Gaussian Mixture Model (GMM): The GMM is trained on the discretized data using MATLAB.
Prediction: The model predicts the closing prices for the last 14 days based on the trained GMM.
