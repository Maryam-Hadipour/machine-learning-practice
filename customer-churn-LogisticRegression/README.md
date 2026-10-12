# Logistic Regression Customer Churn Prediction

This project uses the Telco Customer Churn dataset to explore customer churn and train a Logistic Regression classifier.

## Files

This project uses the Telco Customer Churn dataset, originally published as IBM sample data.

Download `WA_Fn-UseC_-Telco-Customer-Churn.csv` from the Kaggle dataset page and place it in the same folder as `customer-churn-LogisticRegression.ipynb` before running the notebook.

The dataset is not included in this repository.

## How to Run

1. Download or clone this repository.

2. Install Python.

3. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Open `customer-churn-LogisticRegression.ipynb` in Jupyter Notebook, JupyterLab, or VS Code.

5. Run the cells from top to bottom.

The CSV file is read from the same folder as the notebook, so keep both files together.

## What the Notebook Does

* Loads and inspects the data.
* Visualizes churn against several customer features.
* Prepares numerical and categorical columns.
* Splits the data into training and test sets.
* Builds a preprocessing and Logistic Regression pipeline.
* Uses `GridSearchCV` with `ShuffleSplit` to tune Logistic Regression hyperparameters.
* Evaluates model performance using classification reports and cross-validation scores.
* Trains the final model on the full dataset and saves it as `final_LogisticRegression_churn_model.pkl`.

## Note

Before making the repository public, check the dataset source and its license or terms to make sure redistribution is allowed. This is a learning project; model metrics are estimates and do not guarantee real-world performance.
