# AutoEncoder (AE)

An AutoEncoder is a type of artificial neural network used for unsupervised learning. It consists of two main parts:  
- **Encoder**, which compresses the input into a smaller, latent representation.  
- **Decoder**, which attempts to reconstruct the original input from this compressed representation.  

By learning to minimize the difference between the input and its reconstruction, Autoencoders discover compact, meaningful patterns in the data.  

Autoencoders are widely used for:  
- **Unsupervised anomaly detection**, where reconstruction errors highlight unusual data points  
- **Dimensionality reduction and feature learning**, as an alternative to methods like PCA  
- **Denoising and data compression**, by reconstructing clean inputs from noisy data  
- **Pretraining and representation learning**, to initialize deeper architectures  

This notebook demonstrates how to use a dense AutoEncoder in **PyTorch** to detect fraudulent transactions in the **Credit Card Fraud** dataset. The model is trained only on normal transactions, and unusually high reconstruction errors are used to flag anomalies. Performance is evaluated with ROC-AUC, Precision-Recall, and a confusion matrix, alongside visualizations of error distributions and latent-space structure.




## Prerequisites

Ensure you have **Python 3** and **pip** installed. If not, you can download Python from [python.org](https://www.python.org/).

To run this notebook you will need:
- pandas  
- numpy  
- torch  
- scikit-learn  
- matplotlib  
- seaborn

Install with:

```
pip install pandas numpy torch scikit-learn matplotlib seaborn
```
> **NOTE:** The dataset `creditcard.csv` is available from Kaggle [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). Download and place it in the `data` folder before running the notebook.