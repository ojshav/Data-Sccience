# Boston House Price Prediction Machine Learning Project

Welcome to Boston, Massachusetts in the 1970s! In this machine learning project, we'll step into the shoes of real estate developers and build a model to estimate residential property prices based on various characteristics of the homes. Our goal is to provide accurate price estimates to help make informed decisions before starting any real estate development project.

## Project Overview

The project utilizes the famous Boston House Price Dataset, which contains 13 numeric and categorical predictive attributes. The target variable is the Median Value of owner-occupied homes in $1000's. We'll analyze attributes such as crime rate, residential land zoning, proximity to employment centers, nitric oxides concentration, average number of rooms, pupil-teacher ratio, and more.

## Dataset Characteristics

- **Number of Instances**: 506
- **Number of Attributes**: 13 (plus the target variable)
- **Target Variable**: Median Value (PRICE) - Median value of owner-occupied homes in $1000's
- **Attribute Information (in order)**:
  1. CRIM: Per capita crime rate by town
  2. ZN: Proportion of residential land zoned for lots over 25,000 sq.ft.
  3. INDUS: Proportion of non-retail business acres per town
  4. CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
  5. NOX: Nitric oxides concentration (parts per 10 million)
  6. RM: Average number of rooms per dwelling
  7. AGE: Proportion of owner-occupied units built prior to 1940
  8. DIS: Weighted distances to five Boston employment centers
  9. RAD: Index of accessibility to radial highways
  10. TAX: Full-value property-tax rate per $10,000
  11. PTRATIO: Pupil-teacher ratio by town
  12. B: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
  13. LSTAT: % lower status of the population
  14. PRICE: Median value of owner-occupied homes in $1000's (Target Variable)

## Results Summary

After training the model, we obtained an R-squared value of 0.74 on the test data, indicating a good fit to the actual property prices. A property with average values for all features is estimated to have a value of $20,700. The log price estimate is $3.25, with the estimated property worth at $25,792.0.

## Repository Structure

```
/
|-- data/
|   |-- boston_house_price_dataset.csv
|-- notebooks/
|   |-- boston_house_price_prediction.ipynb
|-- README.md
```

- The **data** directory contains the dataset file `boston_house_price_dataset.csv`, used for model training and evaluation.

- The **notebooks** directory contains the Jupyter Notebook file named `boston_house_price_prediction.ipynb`. This notebook contains the entire machine learning pipeline, including data preprocessing, model training, evaluation, and visualization using Python code.

- The **README.md** file (this file) provides an overview of the project, dataset characteristics, and repository structure.

## Usage

To explore the machine learning model and predictions, follow these steps:

1. Clone the repository to your local machine using the following command:
   ```
   git clone https://github.com/your-username/boston-house-price-prediction.git
   ```

2. Install the required dependencies by running:
   ```
   pip install pandas numpy scikit-learn matplotlib
   ```

3. Open the `boston_house_price_prediction.ipynb` Jupyter Notebook in the **notebooks** directory using Jupyter Notebook or JupyterLab.

4. Execute the code cells to run the data preprocessing, model training, and prediction steps.

5. Feel free to modify the notebook and experiment with different machine learning algorithms or hyperparameters.

## Contributions

Contributions to this project are welcome! If you have any suggestions, improvements, or additional analyses, feel free to open an issue or submit a pull request.

When contributing to this repository, please ensure that your code adheres to best practices and is well-documented. Clearly explain the purpose and approach of your contribution.

