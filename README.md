# Credit Card Fraud Detection

This project aims to detect credit card fraud using various machine learning models. The dataset used for this project is the [Credit Card Fraud Detection dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud) available on Kaggle.

## Table of Contents

- [Installation](#installation)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Modeling](#modeling)
- [Evaluation](#evaluation)

## Installation

To run this project, you need to have Python and the required libraries installed. Use the following command to install the necessary libraries:

```sh
pip install -r requirements.txt
```

## Data Preprocessing

The dataset contains transactions made by credit cards in September 2013 by European cardholders. It is highly imbalanced, with the positive class (frauds) accounting for 0.172% of all transactions. Data preprocessing steps include handling missing values, feature scaling, and dealing with imbalanced classes using techniques like SMOTE and RandomOverSampler.

## Exploratory Data Analysis

Exploratory Data Analysis (EDA) helps in understanding the dataset by visualizing the distribution of different features and identifying correlations. Key steps include:

- Checking the count and percentage distribution of normal vs. fraudulent transactions.
- Visualizing the data using bar charts and heatmaps.

## Modeling

Various machine learning models are implemented and compared to detect fraudulent transactions. These models include:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Random Forest Classifier
- AdaBoost Classifier
- XGBoost Classifier

## Evaluation

Model evaluation is performed using metrics like accuracy, ROC-AUC score, precision, recall, and confusion matrix. Cross-validation techniques such as RepeatedKFold are used to ensure the robustness of the models.

## Usage

To run the models and evaluate their performance, execute the following commands:

1. Preprocess the data.
2. Split the dataset into training and testing sets.
3. Train the models.
4. Evaluate the models using the test set.

## Results

The results of the models are compared based on their accuracy, ROC-AUC scores, and other evaluation metrics. The performance of each model is visualized using ROC curves and confusion matrices.

## Conclusion

This project demonstrates the application of various machine learning models to detect credit card fraud. It highlights the importance of data preprocessing, dealing with imbalanced data, and model evaluation in developing an effective fraud detection system.

---

Feel free to explore the code and modify it to improve the model's performance or adapt it to your specific use case.
