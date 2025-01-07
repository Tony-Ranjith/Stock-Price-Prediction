

# Stock Price Prediction

This project is a **Stock Price Prediction system** built with Dash and Python, providing interactive visualizations and forecasting capabilities for financial analysis. Users can view historical stock data, analyze trends, and predict future prices using machine learning models.

## Features
- **Interactive Stock Search**: Search and select stocks by ticker symbol.
- **Historical Data Visualization**: View stock opening and closing prices over time.
- **Trend Analysis**: Analyze stock performance with Exponential Moving Averages (EMA).
- **Stock Price Forecasting**: Predict future stock prices using machine learning (SVR).
- **Dynamic Date Range**: Select custom date ranges for stock data visualization.

## Getting Started

### Prerequisites
- Python 3.x
- **Libraries**: dash, yfinance, pandas, plotly, scikit-learn

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Tony-Ranjith/Stock-Price-Prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Stock-Price-Prediction
   ```
3. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Project
1. Start the Dash application:
2. Run the app.py File
   ```bash
   python app.py
   ```
3. Open your web browser and navigate to http://127.0.0.1:8050/.

## How It Works
1. **Data Retrieval**: Fetches historical stock data using the yfinance library
2. **Visualization**: Uses Plotly for interactive charts, showing stock trends and EMA.
3. **Forecasting**: Implements machine learning with Support Vector Regression (SVR) to predict future prices.
4. **User Interaction**: Accepts user inputs for stock ticker, date range, and forecast duration.
## Results
  The application provides accurate stock price visualizations and reliable forecasts, helping users make informed financial decisions
## Future Improvements
- Integrate more advanced machine learning models (e.g., LSTM, XGBoost) for better predictions.
- Enhance the user interface with additional financial indicators.
- Deploy the application online using platforms like Heroku or AWS.
