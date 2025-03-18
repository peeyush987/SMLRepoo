# Stock Market Prediction App

This project uses machine learning to predict stock market prices based on historical data. The model is built using **Keras** and uses data to generate predictions, which are visualized in a **Streamlit** web app.

## Project Overview

The app loads historical stock market data, processes the data for training and testing, and then predicts the future stock prices. The results are displayed as visualizations for the user to analyze. 

Key features include:
- **Historical Data Loading**: Loads stock data from a CSV file.
- **Data Preprocessing**: Scales and transforms the data using **MinMaxScaler**.
- **Stock Price Visualization**: Displays moving averages (50, 100, and 200 days) and compares actual prices with predicted prices.
- **Stock Price Prediction**: Uses a pre-trained model to predict future stock prices.

## Project Structure

- stock_prediction_model/
  - Stock Predictions Model.keras   # Pre-trained model file
  - EW-MAX.csv                      # Historical stock data file
- app.py                            # Streamlit app code
- requirements.txt                  # Dependencies file

## Requirements

To run this project, you'll need the following libraries:

-numpy
-pandas
-keras
-streamlit
-matplotlib
-scikit-learn

## How to Run

Clone the repository:

git clone <repository_url>
cd stock_prediction_model

Install the required dependencies using the requirements.txt file:
pip install -r requirements.txt

Run the Streamlit app:
streamlit run app.py

Open the Streamlit web app in your browser. The app will display:
Historical stock data in a tabular form.

Stock price trends against moving averages (MA50, MA100, MA200).
A comparison of original vs. predicted stock prices.


## Conclusion

This project is a basic demonstration of using machine learning to predict stock prices using historical data. The Streamlit app allows users to visualize stock trends and compare predictions with actual prices.
