# ML-Regression-Medical-Insurance-prediction
Using various regression models to predict which model gives more accuracy in predicting the insurance amount.

## Project Overview
This project use various regression models and they are:  Multiple Linear regression,Polynomial Regression model,Support Vector Regression, Decision Tree Regression and Random Forest Regression model to find which model works best to find the cost of insurance based on various factor like age, sex,	bmi, children,smoker and region.

## Project Objectives
To build a model to predict the cost of medical insurance based on certain atrributes/values provided by the customer.
This model can help insurance provider to determine the insurance value for a customer.

Link to the dataset: https://www.kaggle.com/datasets/mirichoi0218/insurance

## Project Phases
There were no null values in the data.

### Data Preprocessing & Feature Engineering
- One-hot encoding for categorical variables like sex(Male/Female), and Region (southeast,southwest,northeast and northwest)
- Applying label Encoder on the column "smoker" (value yes/no).
- Splitting the data in Test Set and Training set.

### Model Selection & Fine Tuning
- Training multiple models like  Multiple Linear regression,Polynomial Regression model,Support Vector Regression, Decision Tree Regression
  and Random Forest Regression model.
- Evauluating model performance using accuracy score and scatter plots.
