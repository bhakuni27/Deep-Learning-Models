# Recurrent Neural Network (RNN)

A Recurrent Neural Network (RNN) is a type of neural network designed to model **sequential data** by maintaining a memory of previous inputs through internal loops. This makes RNNs especially powerful for tasks where the **order of data matters**, such as time series forecasting, natural language processing, and speech recognition.

Unlike feedforward networks, RNNs retain context across time steps, allowing them to learn patterns and dependencies in sequences, ideal for analyzing trends over time.

RNNs are widely used for:
- Time series forecasting (e.g., stock prices, weather, energy consumption)
- Natural language modeling and text generation
- Speech and audio processing
- Sequential decision making

The goal of this notebook is to develop an **RNN-based stock price prediction model** using historical stock data from **Apple Inc. (AAPL)**, fetched via the `yfinance` API. The model learns to forecast the **next-day closing price** based on trends observed over the previous 30 days.

## Prerequisites

Ensure you have **Python 3** and **pip** installed. You can download Python from python.org.

To run this notebook, you'll need the following libraries:
- tensorflow
- yfinance
- numpy
- matplotlib
- seaborn
- scikit-learn

To install them, run:
```
pip install tensorflow yfinance numpy matplotlib seaborn scikit-learn
```
> NOTE: The dataset will be fetched using the `yfinance` API, no manual download required.

## Conclusion

The RNN model effectively captured temporal patterns in historical stock data, learning to predict **next-day closing price trends** based on the **past 60 days**. While it does not replicate exact prices, it tracks **directional movement well**, making it useful for trend-based analysis. Some deviation remains during periods of high volatility, suggesting potential improvements through additional features or more complex architectures.

Below is a plot comparing the actual and predicted closing prices for Apple Inc. (AAPL):
![Actual vs Predicted Closing Prices](result\rnn_prediction.png)
