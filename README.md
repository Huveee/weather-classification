# Weather Classification

A machine learning notebook that predicts the weather type (`WeatherType`) from temperature, humidity, wind speed, precipitation, cloud cover, atmospheric pressure, UV index, season, visibility and location.

## What's inside

- **Exploratory analysis:** distributions, box plots, histograms, correlation matrix and pair plots
- **Preprocessing:** IQR-based outlier replacement with the median, ordinal, one-hot and label encoding, standardization, and a 75/25 train/test split
- **Models:** Decision Tree, K-Nearest Neighbors, Gaussian Naive Bayes, SVM, Logistic Regression and a Keras neural network (with dropout, early stopping and Keras Tuner variants)
- **Evaluation:** grid search, k-fold cross-validation, confusion matrices, classification reports and ROC curves

## Running it

The notebook was written for Google Colab and reads its data from Google Drive. The dataset, `weather_classification_data.csv`, is not included in this repository, so add your copy and update the path in the "Importing the dataset" cell.

Outside Colab, install the dependencies first:

```bash
pip install numpy pandas matplotlib seaborn scipy scikit-learn tensorflow keras-tuner
```
