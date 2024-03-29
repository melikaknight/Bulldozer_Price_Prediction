# Bulldozer Price Regression

## Project Overview

This project aims to predict the sale price of bulldozers using historical sales data. The model is built using machine learning techniques, with a focus on regression analysis.

## Data

The dataset used in this project includes information about the sale price of bulldozers, along with various attributes such as model type, usage hours, and manufacturing year. The data is split into training, validation, and test sets.

- Training data: Used to train the model.
- Validation data: Used to tune the model's hyperparameters and evaluate its performance.
- Test data: Used to assess the model's final performance.

The data files include:

- `Train.csv`: Training data
- `Valid.csv`: Validation data
- `Test.csv`: Test data
- `ValidSolution.csv`: Solution file for the validation data

## Model

The model used in this project is a Random Forest Regressor, which is a popular choice for regression problems. The model is trained on the training data and evaluated on the validation data.

## Evaluation

The model's performance is evaluated using the Root Mean Squared Logarithmic Error (RMSLE) metric. The goal is to minimize this error to improve the model's accuracy in predicting bulldozer prices.

## Usage

To run the model and make predictions, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/bulldozer-price-regression.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter notebook:

    ```bash
    jupyter notebook end-to-end-bulldozer-price-regression.ipynb
    ```

