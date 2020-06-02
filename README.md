# Anomaly-Detection-Autoencdoer
Autoencoder is used to detect the anomaly in the dataset

## About

* Here, Firstly I train the autoencoder on the **Non-Fraud Transaction(Noraml Transaction)**

* Then, I use the **Latent Representation of the Input of the autoencoder** and use the weights of the autoencoder is used till latent representation in  the model to make a Sequental model.

* Now, Whole raw data containig both fraud and non-fradulent transaction is given to the new model created using Latent representation and now the data represenatation is changed from the actual data

* Now , Use this simplified data to feed any Machine Learning model to catch any Fradulent case

### Note 
 **In this model, I used both logistic regression and neural networks to catch the fraud cases**
 **For data Visualisation, I used TSNE(t-Distributed Stochastic Neighbor Embedding)**
 
 ### Dataset
 
***For training and testing this model, the data has been taken from the[Credit Card Fraud Detection by ULB machine learning group](https://www.kaggle.com/mlg-ulb/creditcardfraud)***

## Data Representation

**Actual Data**

<img src="Actual Data Represenatation.png">

**Latent Representation of the Actual Data**

<img src="Latent Representation.png">

# Result
***The Accuracy of this model is upto 99.8% on both Logistic Regression and Neural Network***
