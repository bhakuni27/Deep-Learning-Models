# Artificial Neural Network (ANN)

An Artificial Neural Network (ANN) is a computational model inspired by the structure and function of the human brain. It consists of layers of interconnected neurons (nodes) that transform input data through weighted connections and non-linear activation functions.

Each neuron processes incoming data, applies weights and biases, and passes the result through an activation function. By adjusting these weights through **backpropagation** and **gradient descent**, the network learns to make accurate predictions.

ANNs are especially effective for:
- Classification and regression tasks
- Modeling complex, non-linear relationships
- Applications involving structured data, images, or time series

The goal of this notebook is to develop a binary classification model using a simple feedforward ANN to predict whether a bank customer will **churn** (i.e., leave the service), based on features like credit score, age, tenure, balance, and activity history.

## Prerequisites

Ensure you have **Python 3** and **pip** installed. If not, you can download Python from [python.org](https://www.python.org/).

To run this notebook, you’ll need the following libraries:
- tensorflow
- scikit-learn
- pandas
- numpy
- seaborn
- matplotlib

To install the required libraries, run:

```
pip install tensorflow scikit-learn pandas numpy matplotlib seaborn
```

## Conclusion

The ANN model performed well in predicting customer churn, achieving **80% accuracy** and an **AUC score** of **0.864**. The model effectively identifies customers likely to churn, making it a good baseline for future improvements such as hyperparameter tuning or deeper architectures.