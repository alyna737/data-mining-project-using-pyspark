# data-mining-project-using-pyspark
A PySpark-based machine learning project for predicting heart disease using clinical data. Implements Random Forest, Logistic Regression, and K-Means to evaluate classification performance, with Random Forest achieving the highest accuracy and AUC score.
## Features
- Dataset: 14 selected attributes from Cleveland dataset
- Preprocessing: Null value handling, encoding, vector assembling
- Models Used:
  - Random Forest Classifier (Best Performance - AUC: 1.00)
  - Logistic Regression (Good Performance - AUC: 0.93)
  - K-Means Clustering (Exploratory - Low accuracy)
- Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, ROC Curve
- Tools: PySpark MLlib, matplotlib, seaborn

## Setup
Run on Google Colab with PySpark setup. All dependencies are standard Python libraries or available in Colab.

## Conclusion
Random Forest outperformed other models with perfect classification results, highlighting its robustness for heart disease prediction.
