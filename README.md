# Predicting Credit Card Default Risk using Neural Networks
## Problem Description:
The goal of this project is to predict the probability of credit card default for customers. This involves building a credit risk model using neural networks.

## Dataset Description:
The dataset used for this project is "default of credit card clients," sourced from the University of California Irvine (UCI) Machine Learning Repository. It contains a total of 30,000 samples with 24 predictor variables (X) and one continuous target variable (Y).

### Libraries Used:
pandas: For data manipulation and analysis.
numpy: For numerical operations.
scikit-learn: For implementing machine learning algorithms, data preprocessing, and model evaluation.
matplotlib and seaborn: For data visualization.
xlrd: For reading Excel files.

### Functions Defined:
relaciones_vs_target: Function to visualize scatter plots of predictor variables against the target variable.
represento_doble_hist: Function to plot histograms of two probability distributions on the same graph.
hist_pos_neg_feat: Function to represent predictor variables divided into two distributions based on the target variable's values.


### Feature Engineering:
The dataset is split into predictor variables (X) and the target variable (Y).

### Exploratory Data Analysis (EDA):
Basic statistics like mean, standard deviation, minimum, maximum, and quartiles are displayed.
Boxplots and histograms are visualized to understand the distribution of variables.
Correlation matrix and correlation with the target variable are calculated and displayed.

### Data Preprocessing:
The data is standardized using StandardScaler from scikit-learn.

### Model Building:
A Multi-layer Perceptron (MLP) classifier is used for this classification task. Grid search cross-validation is performed to find the best hyperparameters for the model.

### Model Evaluation:
The best hyperparameters found during grid search are printed along with the ROC AUC score.
The model is trained with the best parameters.
Predictions are made on the test set, and the Receiver Operating Characteristic (ROC) curve is plotted.
Confusion matrix, accuracy, sensitivity, and precision scores are available 

## Conclusion:
The model achieved an accuracy of 82% on the test set.
