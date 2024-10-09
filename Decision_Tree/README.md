# Decision Tree

Decision tree is a type of supervised learning algorithm that is mostly used in classification problems. It works for both continuous as well as categorical output variables. It is a tree-structured classifier, where internal nodes represent the features of a dataset, branches represent the decision rules and each leaf node represents the outcome.

The main objective of the decision tree algorithm is to create a training model that can use to predict the class or value of the target variable by learning simple decision rules inferred from prior data(training data).

## Project Objective

The main objective of this project is to predict whether a person  should be granted loan based on the given features. The dataset contains the following features:
- Initial Payment
- Last Payment
- Credit Score
- House Number

and the target variable is:
- Result

### Steps involved in the project are:
1. Load the dataset
2. Checking for missing values
3. Extracting dataset information
4. Data visualization
5. Splitting the dataset into training and testing set
6. Training the model
7. Evaluating the model

## Requirements
the following libraries are required to run the project:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Installation

- ### using `pip`
cd into the project directory and run the following command:

```bash
pip install -r requirements.txt
```

- ### using `conda`
cd into the project directory and run the following command:

```bash
conda install --file environment.yml
```

