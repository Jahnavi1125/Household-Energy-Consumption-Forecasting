# Household Energy Consumption Forecasting

Forecasts household electricity consumption with an LSTM and compares it against an ARIMA baseline.

**Tech:** Python, TensorFlow/Keras, Pandas, NumPy, Statsmodels, Matplotlib

## Dataset
UCI Individual Household Electric Power Consumption dataset.

## Approach
1. Clean and preprocess the sequential consumption data
2. Convert it into time-series input windows
3. Train an LSTM model for forecasting
4. Train an ARIMA model as a baseline
5. Compare both on the same test period


## How to Run
```bash
pip install tensorflow pandas numpy matplotlib statsmodels scikit-learn
```
Open the notebook in Jupyter and run the cells in order.

## Future Improvements
- Try GRU and Transformer-based forecasting models
- Tune the window size and hyperparameters
