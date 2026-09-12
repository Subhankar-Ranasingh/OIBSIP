# Car Price Prediction with Machine Learning

## Objective

The objective of this project is to predict the price of used cars using machine learning techniques.

## Dataset

The dataset contains information about used cars, including:

- Brand
- Model
- Model Year
- Mileage
- Fuel Type
- Engine
- Transmission
- Accident History
- Clean Title
- Price

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Loaded the dataset
2. Checked data types and missing values
3. Cleaned mileage and price columns
4. Performed Exploratory Data Analysis
5. Selected important features
6. Encoded categorical features
7. Split the data into 80% training and 20% testing
8. Trained Linear Regression and Random Forest models
9. Evaluated model performance
10. Compared the models

## Model Results

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 28911.94 | 138697.82 | 0.0588 |
| Random Forest | 27090.58 | 137365.06 | 0.0768 |

## Best Model

Random Forest Regressor performed better than Linear Regression because it achieved lower MAE and RMSE and a higher R² score.

## Conclusion

This project demonstrates the complete machine learning workflow for used car price prediction, including data cleaning, exploratory data analysis, feature selection, encoding, model training, prediction, and evaluation.

## Author

Subhankar Ranasingh