# Annual-Income-Prediction-with-Machine-Learning
Here I've shared the Python code for predicting income levels using machine learning techniques. The dataset I used is the "Adult" dataset, which includes various features such as education, work class, marital status, and more.

# Dataset
I load the dataset using Pandas and perform initial exploratory data analysis to understand the distribution of values in different columns.

# Data Preprocessing
I apply several preprocessing steps to prepare the data for training a machine learning model. This includes one-hot encoding categorical variables, encoding non-numerical attributes to binary, and dropping unnecessary columns.

# Correlation Analysis
I generate correlation matrices and heatmaps to visualize the relationships between different features and the target variable (income). My goal is to identify and retain the most relevant features for building a predictive model.

# Feature Importance
I train a Random Forest Classifier on the preprocessed data and analyze the model's feature importances to understand which features contribute the most to predicting income levels.

# Model Training
I train the Random Forest Classifier on the dataset and evaluate its accuracy on a test set. The initial accuracy is reported, showing the model's ability to predict income levels with an 85% accuracy.

# Hyperparameter Tuning
I use GridSearchCV to perform hyperparameter tuning on the Random Forest model. I determine the optimal set of hyperparameters and re-evaluate the model for accuracy.

# Updated Feature Importance
After hyperparameter tuning, I recalculate the feature importances, providing insights into the most influential factors affecting income prediction.

Feel free to explore my Jupyter Notebook to delve deeper into the code and analysis. I welcome contributions and suggestions
