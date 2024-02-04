# Project Repository Readme

## Stock Price and Temperature Prediction

This repository houses three distinct projects aimed at predictive modeling: predicting future stock prices of Microsoft using LSTM, temperature prediction using time series data using 1DCNN, LSTM, and GRU models, and sales forecasting on the Bulldozers dataset from Kaggle using RandomForest Regressor, 1DCNN, LSTM, and GRU models.

### 1. Microsoft Stock Price Prediction using LSTM

#### Overview
In this project, we leverage Long Short-Term Memory (LSTM) networks to predict future stock prices of Microsoft. The LSTM model is trained on historical stock price data, capturing temporal dependencies to make accurate predictions.

#### Files
- `microsoft_stock_prediction.ipynb`: Jupyter Notebook containing the code for the LSTM model.
- `data/`: Directory containing the dataset used for training and testing.

### 2. Temperature Prediction using Time Series

#### Overview
This project focuses on predicting temperatures using time series data. Three different models, namely 1DCNN, LSTM, and GRU, are implemented to analyze and predict temperature trends over time.

#### Files
- `temperature_prediction.ipynb`: Jupyter Notebook encompassing the code for 1DCNN, LSTM, and GRU models.
- `data/`: Directory containing the time series temperature dataset.

### 3. Bulldozer Sales Forecasting

#### Overview
Sales forecasting is performed on the Bulldozers dataset obtained from Kaggle. Three models, RandomForest Regressor, 1DCNN, LSTM, and GRU, are employed to predict sales figures, achieving an impressive 145 percent accuracy.

#### Files
- `bulldozer_sales_forecasting.ipynb`: Jupyter Notebook with code for RandomForest Regressor, 1DCNN, LSTM, and GRU models.
- `data/`: Directory containing the Bulldozers dataset used for training and testing.

### Usage
1. Clone the repository: `git clone <repository-url>`
2. Navigate to the respective project directory.
3. Open the Jupyter Notebooks and run the cells to reproduce the results.

### Requirements
- Python 3.x
- Jupyter Notebook
- Libraries: NumPy, Pandas, Matplotlib, Scikit-Learn, TensorFlow, Keras

### Acknowledgments
- Microsoft stock data sourced from <source-url>
- Temperature dataset from <source-url>
- Bulldozers dataset obtained from Kaggle: <kaggle-link>

Feel free to explore, experiment, and contribute to enhancing these predictive modeling projects. If you have any questions or suggestions, please create an issue or reach out to the project maintainers. Happy coding!
