# Predicting-crime-rates

A data science project focused on predicting `ViolentCrimesPerPop`. The repository contains a Jupyter notebook comparing regression models and a neural network.

The project is described as a group assignment completed as part of a Data Science specialization.

## Analysis Workflow

The notebook covers:

- Data retrieval and preparation.
- Loading the `dane.csv` dataset.
- Handling missing values represented by `?`.
- Removing columns with many missing values.
- Selecting input features.
- Exploring the distribution of the target variable, `ViolentCrimesPerPop`.
- Visualizing the correlation matrix.
- Splitting the data into training and test sets.
- Training and comparing models.
- Visualizing predictions and residuals.
- Comparing evaluation metrics in tables.

## Models

- Linear regression
- Lasso regression
- Ridge regression
- Polynomial regression of degree 2
- Polynomial regression of degree 3
- Random Forest Regressor tuned with `GridSearchCV`
- A Keras/TensorFlow neural network with Dense and Dropout layers

## Evaluation Metrics

The models are compared using:

- MSE
- RMSE
- MAE
- R2

## Tech Stack

- Python
- Jupyter Notebook / Google Colab
- pandas
- NumPy
- matplotlib
- seaborn
- scikit-learn
- TensorFlow / Keras
- requests

## Getting Started

The notebook is configured to run in Google Colab:

1. Open `pro.ipynb` in Google Colab.
2. Mount Google Drive using the code in the notebook.
3. Place `dane.csv` at the path expected by the notebook:

```text
/content/drive/MyDrive/data/dane.csv
```

4. Run the cells in order.

To run the notebook locally, adapt the Google Drive mounting code, update the CSV path and install the required libraries in your Jupyter environment.

Example dependency installation:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow requests
```

## Project Structure

```text
Predicting-crime-rates/
├── pro.ipynb               # Analysis and model comparison notebook
├── pro_dokumentacja.pdf    # Project documentation
└── README.md
```

## Notes

The repository does not include `dane.csv`. Running the complete analysis requires a separate dataset with the columns used in the notebook.
