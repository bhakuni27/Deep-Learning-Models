# Restricted Boltzmann Machine (RBM)

A Restricted Boltzmann Machine (RBM) is a generative stochastic neural network capable of learning a probability distribution over its set of inputs. RBMs are particularly effective for unsupervised learning tasks like **dimensionality reduction**, **feature learning**, and **recommender systems**.

In this notebook, we demonstrate the use of an RBM for building a **movie recommendation system** using the **MovieLens 100K** dataset. By modeling user-item interactions, the RBM learns latent preferences and suggests movies a user is likely to enjoy, even if they haven't rated them yet.

RBMs are widely used for:
- Collaborative filtering and recommender systems
- Dimensionality reduction
- Pretraining deep neural networks (as part of Deep Belief Networks)
- Feature extraction for unsupervised learning

The goal of this notebook is to implement an RBM using **PyTorch**, train it on binary user-item interaction data, and generate movie recommendations based on learned user preferences.

## Prerequisites

Ensure you have **Python 3** and **pip** installed. If not, you can download Python from [python.org](https://www.python.org/).

To run this notebook, you'll need the following libraries:
- pandas
- numpy
- torch
- matplotlib
- scikit-learn

To install them, run:
```
pip install pandas numpy torch matplotlib scikit-learn
```
