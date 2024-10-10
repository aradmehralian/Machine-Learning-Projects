# Baysian Classification

Baysian classification is a probabilistic classification method based on the Bayes theorem. It is a simple and effective method for classification. It is based on the assumption that the features are independent of each other. It is also known as Naive Baysian classification.

### Bayes Theorem

Bayes theorem is a mathematical formula that calculates the probability of an event occurring, based on prior knowledge of conditions that might be related to the event. It is used to calculate the probability of a hypothesis given the observed evidence.

The formula for Bayes theorem is given by:

```math
P(A|B) = P(B|A) * P(A) / P(B)
```

Where:

- P(A|B) is the probability of event A given that event B has occurred.
- P(B|A) is the probability of event B given that event A has occurred.
- P(A) is the probability of event A.
- P(B) is the probability of event B.

## Project Objective

The project is divided into two parts each has its own notebook in `src/` directory. 

1. **Diabetes Prediction**: The main objective of this project is to predict whether a person has diabetes or not based on the given features. The dataset contains the following features:
   - Hypertension
   - Heart disease
   - Gender
   - Age
   - BMI
   - Smoking history

   and the target variable is:
   - diabetes

2. **Breast Cancer Prediction**: The main objective of this project is to predict whether a person has breast cancer or not based on the given features. The dataset contains the following features:
   - Clump Thickness
   - Uniformity of Cell Size
   - Uniformity of Cell Shape
   - Marginal Adhesion
   - Single Epithelial Cell Size
   - Bare Nuclei

   and the target variable is:
   - Breast cancer

### Steps taken in the project

1. Load the respective dataset
2. Preprocess the data
3. Split the data into training and testing sets
4. Train the model
5. Evaluate the model


## How to run the project

To run the project, follow the steps below:

1. Clone the repository:

```bash
git clone [repository_url]
```

2. cd into the project directory:

```bash
cd Baysian
```

3. Run each notebook in the `src/` directory.

## Requirements

The project requires the following libraries:

- pandas
- scikit-learn
- seaborn
- matplotlib

## How to install the requirements

- **using `pip`**

go to the project directory and run the following command in the terminal:

```bash
pip install -r requirements.txt
```

- **using `conda`**

go to the project directory and run the following command:

```bash
conda install --file environment.yml
```
