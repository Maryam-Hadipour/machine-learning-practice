# KNN Customer Churn Prediction

This project uses the Telco Customer Churn dataset to explore customer churn and train a K-Nearest Neighbors (KNN) classifier.

## Files

This project uses the Telco Customer Churn dataset, originally published as IBM sample data.

Download WA_Fn-UseC_-Telco-Customer-Churn.csv from the Kaggle dataset page and place it in the same folder as knn_churn.ipynb before running the notebook.

The dataset is not included in this repository.

## How to run

1. Download or clone this repository.
2. Install Python.
3. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Open `knn_churn.ipynb` in Jupyter Notebook, JupyterLab, or VS Code.
5. Run the cells from top to bottom.

The CSV file is read from the same folder as the notebook, so keep both files together.

## What the notebook does

- Loads and inspects the data.
- Visualizes churn against several customer features.
- Prepares numeric and categorical columns.
- Splits the data into training and test sets.
- Builds a preprocessing and KNN pipeline.
- Uses `GridSearchCV` with `ShuffleSplit` to compare a small set of KNN settings.
- Prints classification reports and plots training/test cross-validation scores.
- Saves the best model found by the grid search to `pipe_knn_cls.pickle`.

## Note

Before making the repository public, check the dataset source and its license/terms to make sure redistribution is allowed. This is a learning project; model metrics are estimates and do not guarantee real-world performance.
