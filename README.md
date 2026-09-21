# Time-Series Forecasting with an LSTM

This notebook is a learning exercise in forecasting monthly travel activity with a recurrent neural network. I used the `Miles_Traveled.csv` series to practise the full workflow: exploring a time series, preparing sequences, training an LSTM, and comparing predictions with the held-out period.

The exercise was completed while following the *Python for Time Series Data Analysis* course on Udemy.

## What the notebook covers

- parsing dates and using a time-based index
- inspecting trend and seasonality
- splitting the series without shuffling time
- scaling the training data
- creating supervised sequences with `TimeseriesGenerator`
- training an LSTM in Keras
- reversing the scaling and plotting forecasts against actual values

## Files

- `RNN.ipynb` — the complete analysis and model
- `Miles_Traveled.csv` — the monthly source series

## Running it

Open `RNN.ipynb` in Jupyter Notebook or JupyterLab and run the cells in order. You will need Python with pandas, NumPy, Matplotlib, statsmodels, scikit-learn, and TensorFlow/Keras.

The notebook was originally written with the CSV inside a `Data` directory. In this repository the CSV is at the root, so you may need to change the file path in the loading cell before running it.

## Note

This is an educational notebook, not a production forecasting service. The main value of the repository is the worked modelling process.
