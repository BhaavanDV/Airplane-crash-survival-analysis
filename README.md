# Airplane Crash Survival Analysis

## Overview

This project aims to analyze and predict the survival rates of passengers involved in airplane crashes. Using machine learning models, we explore how various factors such as demographics, seat class, flight details, and others influence the likelihood of survival. The goal is to build a predictive model to assist in understanding the key survival factors in aviation disasters.

## Objective
Explore Data: Investigate the relationships between passenger demographics (age, sex, etc.) and survival rates.
Model Development: Build a predictive model to classify passengers as survivors or non-survivors.
Algorithm Comparison: Assess various machine learning algorithms, such as Logistic Regression, Random Forest, and Support Vector Machines (SVM).

## Dataset

The dataset used contains information on passengers involved in a simulated airplane crash. It includes the following features:

Passenger ID: Unique identifier for each passenger.
Pclass: The passenger’s seat class (1st, 2nd, 3rd).
Sex: Gender of the passenger.
Age: Age of the passenger.
SibSp: Number of siblings or spouses aboard.
Parch: Number of parents or children aboard.
Ticket: Passenger’s ticket number.
Fare: Fare paid by the passenger.
Cabin: The passenger’s cabin number (if available).
Embarked: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton).
Survived: Survival status (0 = No, 1 = Yes).

The data is available through public datasets such as the **[Airplane crash and fatalitites dataset](Airplane_Crashes_and_Fatalities_Since_1908.csv")**, which can be used as a reference for the analysis.

## Workflow

1. **Data Exploration**: Understand the dataset, visualize relationships, and identify important features.
2. **Data Preprocessing**: Clean the data by handling missing values, encoding categorical variables, and scaling numerical features.
3. **Model Training**: Train multiple machine learning models (e.g., Logistic Regression, Random Forest, SVM) and evaluate their performance.
4. **Model Evaluation**: Compare the models using evaluation metrics like accuracy, precision, recall, and F1-score.
5. **Prediction**: Use the best-performing model to predict survival on the test dataset.

## Contributions

Contributions are encouraged! If you would like to improve the analysis, add new features, or optimize the model, feel free to fork the repository and submit pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
