# Iris Flower Classification

A machine learning model that predicts the species of an iris flower — **Setosa**, **Versicolor**, or **Virginica** — based on sepal and petal measurements.

## What it does

- Loads the classic Iris dataset (150 samples, 4 features, 3 species)
- Performs exploratory data analysis with pairplots and a correlation heatmap
- Trains a K-Nearest Neighbors classifier on scaled features
- Evaluates the model with accuracy, a classification report, and a confusion matrix
- Predicts the species for a new, unseen flower measurement

## Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook (for interactive exploration)

## How to run

pip install -r requirements.txt
python iris_classification.py

This will print the model's accuracy and classification report to the console, and save three visualizations to the project folder:

- pairplot.png — feature relationships by species
- correlation_heatmap.png — feature correlation matrix
- confusion_matrix.png — model prediction accuracy by class

## Results

The K-Nearest Neighbors model achieves **~93% accuracy** on the held-out test set, with perfect classification of Setosa (the most visually distinct species) and strong performance on Versicolor and Virginica.

## Author

Devipriya Chintha
