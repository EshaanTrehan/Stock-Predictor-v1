
# Stock Predictor v36 📈

Explore the fascinating domain of stock prediction with **Stock Predictor v36**. This Python-based tool empowers users to predict stock prices for a specified company using LSTM neural networks. By harnessing historical data, the application provides insights into potential future stock performance.

## 🚀 Features

- **Stock Data Retrieval**: Fetch historical stock data for a specified company from Yahoo Finance.
- **Visualizations**: Analyze stock trends through closing price versus time charts, as well as 50-day and 200-day moving averages.
- **LSTM Neural Network**: Leverage the power of LSTM neural networks for stock prediction.
- **Interactive UI**: Use a user-friendly interface powered by `streamlit` to select stocks, visualize data, and view predictions.
- **Prediction Accuracy**: Evaluate the accuracy of predictions through a comparison graph and the mean absolute error metric.

## 📁 File Structure

- 📄 `stock.py`: The heart of the application, containing logic for data retrieval, machine learning prediction, and visualization.
- 📜 `keras_model.h5`: Pre-trained LSTM neural network model used for stock prediction.

## 🔧 Setup & Execution

1. Install the required Python libraries:
   ```bash
   pip install numpy pandas matplotlib pandas_datareader keras streamlit sklearn
   ```
2. Launch the application using `streamlit`:
   ```bash
   streamlit run stock.py
   
   ```
3. Navigate to the web interface, enter a stock ticker (e.g., AAPL for Apple Inc.), and explore the predictions and visualizations.

## 🧠 Technical Insights

- **Data Source**: Stock data is fetched from Yahoo Finance, providing a reliable dataset for predictions.
- **Neural Network**: The application employs LSTM neural networks known for their proficiency in time series predictions, like stock prices.
- **Data Visualization**: `matplotlib` is utilized to generate intuitive charts, aiding in the analysis of stock trends and prediction accuracy.

## 🧪 Testing

1. Execute the application using the aforementioned steps.
2. Enter various stock tickers to test the prediction capability of the application.
3. Analyze the prediction graph to understand the efficacy of the LSTM model.
4. Observe the mean absolute error to gauge the accuracy of predictions against actual stock prices.
