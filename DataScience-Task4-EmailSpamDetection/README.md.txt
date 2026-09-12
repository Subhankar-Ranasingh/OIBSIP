# Email Spam Detection with Machine Learning

## Project Overview

This project focuses on detecting whether an email or text message is **Spam** or **Ham (Not Spam)** using Machine Learning and Natural Language Processing (NLP).

The project uses **TF-IDF Vectorization** to convert text messages into numerical features and compares two machine learning algorithms:

* Naive Bayes
* Logistic Regression

## Objective

The main objective of this project is to build a machine learning model that can automatically classify messages as Spam or Ham.

## Dataset

The project uses the **Spam/Ham Detection Dataset**.

The dataset contains **5,572 messages**:

* Ham: 4,825
* Spam: 747

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* Natural Language Processing (NLP)

## Project Workflow

1. Load the dataset
2. Clean and prepare the data
3. Remove unnecessary columns
4. Convert labels into numerical values
5. Preprocess text messages
6. Split the dataset into training and testing sets
7. Apply TF-IDF Vectorization
8. Train Naive Bayes model
9. Train Logistic Regression model
10. Evaluate model performance
11. Create a confusion matrix
12. Test the model on a new message

## Model Performance

| Model               | Accuracy |
| ------------------- | -------: |
| Naive Bayes         |   96.05% |
| Logistic Regression |   97.22% |

### Best Model

**Logistic Regression** achieved the highest test accuracy of **97.22%** and performed better than Naive Bayes on this dataset.

## Prediction Example

The final Logistic Regression model was tested with a new message:

> "Congratulations! You have won a free prize. Click now!"

The model predicted:

**Spam**

## Conclusion

This project demonstrates how Natural Language Processing and Machine Learning can be used to classify text messages as Spam or Ham.

TF-IDF was used to convert text into numerical features, while Naive Bayes and Logistic Regression were used for classification.

Among the two models, **Logistic Regression performed better with an accuracy of 97.22%**.

## Author

**Subhankar Ranasingh**
