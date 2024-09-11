# House Price Prediction

This repository contains a comprehensive solution for predicting house prices using machine learning models. The project leverages various techniques including data preprocessing, model training, hyperparameter tuning, and result evaluation.

1. **Data Preparation**:
   - **Loading Data**: Data is loaded from CSV files.
   - **Preprocessing**: Handling missing values, scaling numerical features, encoding categorical features, and preparing the training and test datasets.
   
2. **Model Training and Evaluation**:
   - **Models Used**:
     - Support Vector Regressor (SVR)
     - XGBoost Regressor
     - Ridge Regression
     - ElasticNet Regression
     - SGD Regressor
     - Bayesian Ridge Regression
     - Linear Regression
     - Random Forest Regressor
   - **Model Comparison**: Evaluation of models based on Root Mean Square Error (RMSE) to select the best-performing model.

3. **Hyperparameter Optimization**:
   - **Optuna**: Utilized for hyperparameter tuning of the XGBoost Regressor to find the optimal model parameters.

4. **Prediction and Submission**:
   - **Predictions**: Make predictions on the test dataset using the best model.
   - **Submission File**: Prepare a submission CSV file with predicted house prices.

## File Structure
- `train.csv`: Training dataset containing features and target variable (`SalePrice`).
- `test.csv`: Test dataset containing features (without target variable).
- `sample_submission.csv`: Sample submission file with the correct format for predictions.
- `my_submission.csv`: Output file with predictions for submission.

