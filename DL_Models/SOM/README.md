# Self-Organizing Map (SOM)

A Self-Organizing Map (SOM) is an unsupervised neural network algorithm designed to project high-dimensional data into a lower-dimensional (usually 2D) space, while preserving the topological relationships of the original data. This makes SOMs ideal for **visualizing**, **clustering**, and **discovering patterns** in complex datasets.

Unlike supervised models, SOMs don’t rely on labeled outputs. Instead, they **learn to organize input data** based solely on similarity, making them powerful tools for exploratory data analysis, clustering, and dimensionality reduction.

SOMs are widely used for:
- Visualizing high-dimensional data
- Clustering similar observations
- Detecting patterns or anomalies
- Exploratory analysis in customer segmentation, bioinformatics, and more

This notebook demonstrates the use of a Self-Organizing Map to analyze the classic **Wine dataset**, which includes chemical attributes of wines from three different cultivars. The goal is to **map similar wine profiles** onto a 2D grid and reveal natural groupings without using label information during training.

## Prerequisites

Ensure you have **Python 3** and **pip** installed. If not, you can download Python from [python.org](https://www.python.org/).

To run this notebook, you'll need the following libraries:
- minisom
- pandas
- matplotlib
- seaborn
- scikit-learn

To install them, run:
```
pip install minisom pandas matplotlib seaborn scikit-learn
```
> NOTE: No dataset download is required as the **Wine dataset** is available via `sklearn.datasets`.

## Conclusion

The Self-Organizing Map (SOM) model successfully revealed meaningful patterns in the Wine dataset by organizing samples based on their chemical properties. Through the U-Matrix visualization, it clearly separated different wine classes and highlighted distinct cluster boundaries. This demonstrates SOM’s effectiveness in discovering structure in high-dimensional data without the use of labeled outputs.

![SOM U-Matrix](result/u-matrix.png)
