Title: Stepwise multiple linear regression with cross-Validation for Soil Bulk Density Prediction

Authors: Igor L. Bretas 

Affiliations: University of Florida, North Florida Research and Education Center, 3925 Highway 71, Marianna, FL, 32446, USA

Date: [2025-03-24]

Description:
This Python script performs stepwise multiple regression with 10-fold cross-validation for predicting soil bulk density. The model is trained using a dataset containing physical and chemical soil properties and evaluates performance using RMSE, MAE, and R² metrics.

Requirements & Dependencies:
- pandas (for data manipulation)
- numpy (for numerical operations)
- statsmodels (for regression modeling)
- matplotlib (for visualization)
- sklearn (for cross-validation and error metrics)
- google.colab (for Google Drive file access in Colab)

Install missing dependencies using:
pip install pandas numpy statsmodels matplotlib scikit-learn

Usage Instructions:
1. Update 'file_path' with the location of your dataset.
2. Ensure the dataset includes soil properties like Bulk Density, Soil Order, etc.
3. Run the script using:
   run_analysis(file_path, sheet_name)

Processing Steps:
- Loads and preprocesses data (handles missing values, categorical variables).
- Uses stepwise regression (AICc) to select the best predictors.
- Performs 10-fold cross-validation to evaluate model performance.

Outputs:
- 10Fold_CV_Results.xlsx (cross-validation results)
- Predictions.xlsx (actual vs. predicted values)
- Model_Equation.xlsx (final regression model)
- Model_Coefficients.xlsx (variable importance)

License & Citation:
This script is licensed under MIT. If used in research, please cite:
Bretas et al., "Stepwise multiple linear regression with cross-validation for Soil Bulk Density Prediction", 2025.

For questions, contact: ig.limabretas@ufl.edu
