# Deep Learning Models

This repository is a collection of example implementations of fundamental **deep learning models**. Each model is organized into its own folder and includes:  
- A Jupyter Notebook with step-by-step implementation  
- A mini README explaining the model, dataset, and results  
- Dataset instructions or references  

The goal of this project is to provide clear, hands-on examples of classic deep learning architectures for learning and experimentation.

## Implemented Models

- **Artificial Neural Network (ANN)** – basic feedforward classification  
- **Convolutional Neural Network (CNN)** – image recognition and feature extraction  
- **Recurrent Neural Network (RNN)** – sequence modeling (e.g., text, time series)  
- **Self-Organizing Map (SOM)** – unsupervised clustering and visualization  
- **Restricted Boltzmann Machine (RBM)** – collaborative filtering for recommendations  
- **AutoEncoder (AE)** – anomaly detection using reconstruction error  

## Repository Structure
```
DL_Models/
│
├── AE/
│ ├── data/
│ ├── ae_notebook.ipynb
│ └── README.md
│
├── ANN/
│ ├── data/
│ │ └── Churn_Modelling.csv
│ ├── ann_notebook.ipynb
│ └── README.md
│
├── CNN/
│ ├── cnn_notebook.ipynb
│ └── README.md
│
├── RBM/
│ ├── data/
│ │ └── u.data
│ ├── rbm_notebook.ipynb
│ └── README.md
│
├── RNN/
│ ├── result/
│ │ └── rnn_prediction.png
│ ├── rnn_notebook.ipynb
│ └── README.md
│
├── SOM/
│ ├── result/
│ │ └── u-matrix.png
│ ├── som_notebook.ipynb
│ └── README.md
│
└── README.md ← main repository README (this file)
```

## Getting Started

Clone the repository:

```
git clone https://github.com/bhakuni27/Deep-Learning-Models.git
cd Deep-Learning-Models
```
Each model can be run independently. Refer to the `README.md` inside each folder for dataset download instructions and usage details.