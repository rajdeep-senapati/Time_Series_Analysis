# ARIMA-Based Time Series Forecasting

## Project Overview
This project demonstrates time series forecasting using the **ARIMA (AutoRegressive Integrated Moving Average) model** on the **Airline Passengers dataset**. The dataset contains monthly totals of international airline passengers from 1949 to 1960.

The goal of this project is to train an ARIMA model on historical passenger data and use it to predict future trends while evaluating the model's accuracy.

## Dataset Information
- **Source:** [Airline Passengers Dataset](https://raw.githubusercontent.com/jbrownlee/Datasets/master/airline-passengers.csv)
- **Attributes:**
  - `Month`: Date of observation (YYYY-MM format)
  - `Passengers`: Number of passengers (in thousands)
- **Size:** 144 data points (January 1949 to December 1960)

## Project Workflow
1. **Import Required Libraries**: Load essential Python libraries like Pandas, NumPy, Matplotlib, Statsmodels, and Sklearn.
2. **Load and Preprocess Data**: Read the dataset, set the `Month` column as an index, and check for missing values.
3. **Exploratory Data Analysis (EDA)**:
   - Print the first five rows and summary statistics.
   - Plot the time series to visualize trends and seasonality.
4. **Train-Test Split**: Divide the dataset into 80% training and 20% testing data.
5. **ARIMA Model Training**:
   - Fit an **ARIMA(5,1,0)** model (5 lags, first-order differencing, moving average of 0).
   - Print the model summary to analyze coefficients and statistics.
6. **Forecasting**:
   - Predict values for the test dataset.
   - Plot actual vs. predicted values.
7. **Model Evaluation**:
   - Calculate **Root Mean Squared Error (RMSE)** to measure prediction accuracy.

## Results and Findings
- The ARIMA(5,1,0) model successfully forecasts passenger trends.
- The RMSE metric provides a quantitative measure of model accuracy.
- Visualizing actual vs. predicted data showcases the effectiveness of the model.

## Conclusion
This project illustrates how to use ARIMA for time series forecasting, evaluating its performance on real-world data. The approach is extendable to financial, economic, and business forecasting problems.

## Author
Rajdeep Senapati

