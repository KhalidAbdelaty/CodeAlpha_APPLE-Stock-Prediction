# Stock Price Prediction with LSTM

## Description
This project involves predicting the closing price of Microsoft's stock using a Long Short-Term Memory (LSTM) model. The data spans from 1980 to 2024, providing a rich dataset for the model to learn from.

## Table of Contents
1. Data Preprocessing
2. Exploratory Data Analysis
3. Model Building
4. Model Evaluation

## Data Preprocessing <a name="data_preprocessing"></a>
The first step involved preprocessing the data, checking for null values, and getting a statistical summary of the data. The data was then filtered to include only the records from 2018 to 2024.

## Exploratory Data Analysis <a name="eda"></a>
Next, we visualized the trend in the stock's opening and closing prices with a line plot. This gave a clear picture of how the stock price has changed over time.

## Model Building <a name="model_building"></a>
The 'Close' price was used as the target variable for our prediction model. We split the data into training and test sets, and then scaled it using the StandardScaler from sklearn. Our prediction model was a Long Short-Term Memory (LSTM) model, a type of recurrent neural network that's a perfect match for time series data like stock prices.

## Model Evaluation <a name="model_evaluation"></a>
After training the model, we set it loose on the test set to make predictions. The model achieved an R2 Score of 0.78, indicating that it was able to explain 78% of the variance in the test set. The Mean Squared Error was 0.0, and the Mean Absolute Error was 0.04.

## Repository Link
You can find the entire source code for this project in this repository. Feel free to check it out and explore!
