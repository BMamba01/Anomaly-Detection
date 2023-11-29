
# Anomaly Detection

In this project we are building an AI model for Anomaly Detection in time series dataset using PCA(Principal Component Analysis).

# Description

An anomaly is anything that deviates from what is standard or expected. It can be detected through various methods such as `  Mean Absolute Deviation` and `Isolation Forest`. These are the methods which are usually used for detecting the anomaly. In our project we have used the `Mean Absolute Deviation`. It uses the Robust Z score method wwhich calculates the deviation of data from the mean and return the values which are higher than the threshold set by the user.

 We have also used the `PCA(Principal Component Analysis` for the dimensionality reduction of the dataset. PCA is an unsupervised machine learning model most commly used for dimensionality reduction , exploratory data analysis , data denoising etc. For using the PCA we first have to standardize the data. Then it calculates the covariance matrix, Eigen values, Eigen vectors. It then help us to calculate the Principal Components of the dataset. 
PCA is very helpful when we are using large datasets which will require alot of time for processing and plotting. 

We have taken the Energy Consumption Dataset from the Kaggle for the intial pre processing and training of the data. It is a timeseries dataset by VITTHAL MADANE.




## Tech used
 
We have used the `Kaggle` notebook for the dataset and the ML codes.
## Acknowledgements

We want to thank Dr. Gurwinder Singh sir for his guidance and mentorship throughout this project. 

## Authors

- Naman Nagvanshi
- Chander Thakur
- Saurav Kumar Dani




## Links

- Dataset  https://www.kaggle.com/datasets/vitthalmadane/energy-consumption-time-series-dataset

- Notebook https://www.kaggle.com/code/namannagvanshi/evaluation