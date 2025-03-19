# Titanic_GrowthLink
Data Science Project:

This repository contains a machine learning model to predict whether a passenger survived the Titanic disaster. The model is built using the Logistic Regression algorithm and is trained on the Titanic dataset.

## Dataset

The dataset includes the following features:

- **PassengerId**: Unique identifier for each passenger
- **Survived**: Survival status (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name**: Passenger's name
- **Sex**: Passenger's gender
- **Age**: Passenger's age
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Passenger fare
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Preprocessing Steps

1. **Dropping Unnecessary Columns**: Columns like `PassengerId`, `Name`, `Ticket`, and `Cabin` were dropped as they are not useful for prediction.
2. **Handling Missing Values**: Missing values in the `Age` and `Fare` columns were filled with the mean values of the respective columns.
3. **Encoding Categorical Variables**: The `Sex` and `Embarked` columns were encoded into numerical values.
4. **Splitting the Dataset**: The dataset was split into training and testing sets with a 70-30 split.

## Model Selection

The Logistic Regression model was chosen for this classification task. The model was trained on the training set and evaluated on the testing set.

## Performance Analysis

- **Training Accuracy**: 100%
- **Testing Accuracy**: 100%

## Repository Structure

- `titanic.csv`: The dataset used for training and testing the model.
- `Titanic.ipynb`: The Python script containing the code for data preprocessing, model training.
- `README.md`: This file, providing an overview of the project.

## How to Run the Code

1. Clone the repository.
2. Ensure you have Python and the necessary libraries installed (`numpy`, `pandas`, `scikit-learn`).
3. Run the `Titanic.ipynb` script.

