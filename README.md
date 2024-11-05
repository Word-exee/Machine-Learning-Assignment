
# Machine Learning Assignment-1

## Electricity Bill Dataset Regression Analysis

This part contains the implementation of various regression models and preprocessing techniques on the Electricity Bill Dataset. The dataset is split into 80:20 for training and testing. The project is divided into several tasks as outlined below:

### a)Exploratory Data Analysis (EDA)

Performed pair plots, box plots, violin plots, count plots for categorical features, and a correlation heatmap.
Provided at least five insights based on the visualizations in the report .

### b)Dimensionality Reduction using UMAP

Applied UMAP to reduce the data dimensions to 2 and plotted the results as a scatter plot.
Discussed the separability and clustering of the data after dimensionality reduction.

### c)Preprocessing and Linear Regression

Handled missing values and normalized numerical features.
Categorical features were encoded using LabelEncoding.
Applied Linear Regression and reported evaluation metrics including MSE, RMSE, R2 score, Adjusted R2 score, and MAE for both train and test datasets.

### d)Recursive Feature Elimination (RFE)

Performed RFE or correlation analysis to select the 3 most important features.
Trained a regression model using these selected features and compared the results (MSE, RMSE, R2 score, Adjusted R2 score, MAE) with the results from the full dataset in part (c).

### e)Ridge Regression with One-Hot Encoding

Applied One-Hot Encoding for categorical features and used Ridge Regression.
Reported evaluation metrics and compared the results with Linear Regression in part (c).

### f)Independent Component Analysis (ICA)

Applied ICA with 4, 5, 6, and 8 components and reported evaluation metrics (MSE, RMSE, R2 score, Adjusted R2 score, MAE) for both train and test datasets.
Compared the results for each number of components.

### g)ElasticNet Regularization

Implemented ElasticNet regularization while training a linear model.
Reported evaluation metrics for different values of the mixing parameter (alpha) and compared them with previous results.

h)Gradient Boosting Regressor

Applied Gradient Boosting Regressor on the preprocessed dataset.
Reported evaluation metrics and compared them with those obtained from Linear Regression and ElasticNet in parts (c) and (g).
