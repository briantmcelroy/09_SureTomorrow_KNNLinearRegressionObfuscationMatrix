# 09_SureTomorrow_KNNLinearRegressionObfuscationMatrix

## About this Project

This project seeks to satisfy several different business interests of the hypothetical insurance company Sure Tomorrow. Marketing wishes to identify customers who are similar to select sample customers. The company also wants to be able to predict whether new customers are likely to receive an insurance benefit (classification task). Finally, the company wants to mask the dataset so it can share sensitive customer data without risk. The goal of this project is to satisfy all these multiple business requests with the same dataset.

This project is great for thorough understanding of several data science fundamentals. It demonstrates (1) how to use KNN (K-nearest neighbors) algorithms to identify clusters of customers; (2) how to build a linear regression on a classification task from the ground up; and finally (3) how to mask data to make it hard to recover personal information from a dataset. It also highlights how scaling affects KNN tasks, and completely walks through the linear algebra of data obfuscation. 

## Running it Yourself

The Jupyter notebook is self-contained and reflects the outputs of the code contained within. If you would like to connect to your own environment and run the notebook, or make changes on your own fork of the repo, you may do so after cloning. Make sure the environment is either based in the upper-level folder to which you clone the repo, or be sure to replace the dataset file references with a direct local reference to the /datasets/ folder on your machine. 

The project relies on scikit-learn 1.5.1. Our seaborn package was 0.13.3. The project is stable with Python 3.11.