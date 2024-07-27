# Bitcoin Price Prediction

This project involves predicting Bitcoin prices using an LSTM (Long Short-Term Memory) model. The data used is historical Bitcoin price data, and the model is trained to forecast future prices based on past trends.

## Project Structure

1. **Import Libraries**: Import necessary libraries and functions.
2. **Function Definitions**: Includes functions for data loading, normalization, splitting, preparation, and metric calculation.
3. **Data Loading and Cleaning**: Loads and preprocesses the historical Bitcoin price data.
4. **Visualization**: Plots the closing price and 30-day rolling mean of Bitcoin prices.
5. **Data Normalization**: Scales the data using MinMaxScaler.
6. **Data Splitting**: Divides the data into training, validation, and test sets.
7. **Data Preparation**: Prepares the data for LSTM by creating time steps.
8. **LSTM Model Definition and Training**: Defines and trains the LSTM model for price prediction.
9. **Prediction and Evaluation**: Makes predictions and plots the results. Includes saving and loading the trained model.

## Requirements

Make sure you have the following libraries installed:

- `pandas`
- `matplotlib`
- `seaborn`
- `numpy`
- `scikit-learn`
- `tensorflow`

You can install the required libraries using pip:

```bash
pip install pandas matplotlib seaborn numpy scikit-learn tensorflow
