The project is conducted bsed on the avaiable dataset on Kaggle.com (https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset)
The project is aimed to build a predictive model to identify individuals at risk of diabetes

The project contains 3 files:
- "diabete copy.ipynb" contains all the codes and markdown that execute the project.
- "diabetes_012_health_indicators_BRFSS2015.csv" contains cleaned data for model training.
- "diabetes_model.pkl" is the best model got from "diabete copy.ipynb".

The work above has achieved the following criteria:
- Performing an EDA on individual's society status (age, gender, income)
- Calculating correlation between features using Pearson, Spearman, and Kendall correlation coefficients
- Identifying strong, moderate, and weak correlations between features and the target variable
- Performing feature selection to select the most relevant features
- Splitting the dataset into training and testing sets
- Training and testing to find the best models among the non-linear models for the predictive model.
- Evaluating the the models
- Hyperparameter tuning
- Finding the best models among the non-linear models for the predictive model
- Saving the results and best models for further uses and analysis

Future plans:
- Performing more EDA on other features to gain insights such as health status, nutrient status, physical condition, etc.
- Performing feature engineering to create new features that may improve the performance of the models.
- Using other machine learning algorithms such as Neural Network, Gradient Boosting, etc. to compare the results.
- Testing the best models on an unseen dataset to evaluate their performance.
- Deploying the best models on a GUI application.

Room for improvement:
- The current model is using the entire dataset to train and evaluate. In a real-world scenario, it would be beneficial to perform cross-validation to get a more reliable evaluation.
- The model may not be as accurate as it could be if it had been trained on a larger dataset. In such cases, using more data could help improve the model's performance.
- The model may not be as interpretable as it could be if it used more advanced techniques such as decision tree visualization. In such cases, using simpler models or techniques could help improve the model's interpretability.
