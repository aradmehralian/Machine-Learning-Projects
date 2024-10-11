# SVM 

SVM, which stands for Support Vector Machine, is a powerful supervised machine learning algorithm used for both classification and regression tasks. It operates by identifying the hyperplane that best distinguishes the various classes within the input data. SVM is designed to maximize the margin between classes, making it adept at handling intricate and multifaceted datasets.


## Project Objective

The main objective of this project is to predict whether a person finishes their education based on the given features. The dataset contains the following features:

- Marital Status
- Nationality
- Parent's Education
- Gender
- Age at enrollment  
and etc.

and the target variable is:
* whether the person finishes their education or not

### Steps involved in the project are:
1. Load the dataset

2. Checking for missing values

3. Extracting features and target variable

4. Preprocessing the data

5. Splitting the dataset into training and testing set

6. Training various models such as linear SVM, soft SVM, etc.

## Requirements

The following libraries are required to run the project:
- pandas
- matplotlib
- Scikit-learn
- seaborn

## How to run the project

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

Run each cell in the `src/student_performance_prediction.ipynb` file to train the model and see the results.

