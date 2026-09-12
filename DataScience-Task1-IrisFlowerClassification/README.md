# Iris Flower Classification

## OASIS INFOBYTE – Data Science Internship

**Task:** Task 1 – Iris Flower Classification  
**Intern:** Subhankar Ranasingh

## Objective

The objective of this project is to build a machine learning classification model that can classify Iris flowers into different species using their flower measurements.

## Dataset

The Iris dataset is a well-known dataset used for classification problems.

It contains:

- 150 samples
- 4 numerical features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- 3 species:
  - Setosa
  - Versicolor
  - Virginica

The dataset was loaded directly from `scikit-learn`.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Steps

1. Loaded the Iris dataset.
2. Converted the dataset into a Pandas DataFrame.
3. Checked the shape, columns, data types, and missing values.
4. Performed descriptive statistical analysis.
5. Visualized feature relationships using a pairplot.
6. Created box plots for numerical features.
7. Analyzed feature correlation using a correlation matrix and heatmap.
8. Discussed feature selection and discriminative features.
9. Split the dataset into 80% training and 20% testing data.
10. Trained two classification models:
    - Logistic Regression
    - K-Nearest Neighbors (KNN)
11. Evaluated the models using accuracy, confusion matrix, and classification report.
12. Compared both models and selected the better-performing model.

## Model Results

| Model | Accuracy |
|---|---:|
| Logistic Regression | 96.67% |
| KNN | 100.00% |

## Best Model

K-Nearest Neighbors (KNN) was selected as the best-performing model because it achieved **100% accuracy** on the test dataset, compared with **96.67%** for Logistic Regression.

## Conclusion

The Iris Flower Classification project was successfully completed using machine learning techniques. Two classification models were trained and evaluated. Based on the test results, KNN performed better than Logistic Regression and was selected as the best-performing model.

## Author

**Subhankar Ranasingh**

Data Science Intern – OASIS INFOBYTE