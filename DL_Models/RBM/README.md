# Restricted Boltzmann Machine (RBM)

A Restricted Boltzmann Machine (RBM) is a generative stochastic neural network capable of learning a probability distribution over its set of inputs. RBMs are particularly effective for unsupervised learning tasks like **dimensionality reduction**, **feature learning**, and **recommender systems**.

RBMs are widely used for:
- Collaborative filtering and recommender systems
- Dimensionality reduction
- Pretraining deep neural networks (as part of Deep Belief Networks)
- Feature extraction for unsupervised learning

This notebook demonstrates the implementation of an RBM in **PyTorch** for a **movie recommendation system** using the **MovieLens 100K** dataset. The model learns latent user preferences from historical ratings and generates personalized movie recommendations.

## Prerequisites

Ensure you have **Python 3** and **pip** installed. If not, you can download Python from [python.org](https://www.python.org/).

To run this notebook, you'll need the following libraries:
- pandas
- numpy
- torch
- matplotlib
- seaborn
- scikit-learn

To install them, run:
```
pip install pandas numpy torch matplotlib seaborn scikit-learn
```

## Conclusion

The RBM model was able to capture meaningful patterns in user–item interactions from the MovieLens dataset and achieved solid classification performance with an **AUC of 0.73**. While not perfect, the model demonstrates its ability to reconstruct user preferences and provide a foundation for building recommendation systems. Future improvements could include deeper architectures, hyperparameter tuning, or integrating additional metadata such as genres or user demographics.
