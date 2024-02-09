# Disease Classification using CatBoost

This repository contains code for classifying diseases based on symptoms using CatBoost, a gradient boosting library developed by Yandex. The dataset used for this classification task is provided in `dataset.csv`.

## Requirements

Before running the code, ensure you have the following libraries installed:

- numpy
- pandas
- matplotlib
- catboost
- scikit-learn

You can install the required libraries using pip:

```bash
pip install numpy
pip install pandas
pip install matplotlib
pip install catboost
pip install scikit-learn
```

## Data Preprocessing

The code begins by reading the dataset `dataset.csv` using pandas and extracting unique symptoms and disease names. It then creates a binary representation of the symptoms for each disease and saves the processed data in `train.csv`.

## Model Training

The training data is loaded from `train.csv`, and the CatBoostClassifier is used to train the disease classification model.

## Model Evaluation

The trained model is evaluated on the test data, which is preprocessed and loaded from `test.csv`. The accuracy score of the model on the test data is calculated and printed.

## Usage

To use this code, follow these steps:

1. Install the required libraries as mentioned in the requirements section.
2. Place the `dataset.csv` file in the same directory as the code.
3. Run the code to perform data preprocessing, model training, and evaluation.
4. The accuracy score of the model will be displayed, which indicates how well the model performs on the test data.

Note: Ensure that the dataset is structured as per the code's assumptions, with symptoms as columns and diseases as rows in the CSV file.

Feel free to modify the code or dataset according to your requirements and run the classification task with different data if needed.
