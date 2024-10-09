# Neural Network

Neural Network is a machine learning technique that is designed to simulate the way the human brain works. It is a set of algorithms, modeled loosely after the human brain, that is designed to recognize patterns. They interpret sensory data through a kind of machine perception, labeling, clustering, and categorizing data.

The main objective of the neural network algorithm is to create a training model that can use to predict the class or value of the target variable by learning simple decision rules inferred from prior data(training data).

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

6. Training the model

## Requirements

The following libraries are required to run the project:
- pandas
- matplotlib
- Keras
- Scikit-learn

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

Run each cell in the `src/neural_network.ipynb` file to train the model and make predictions.
