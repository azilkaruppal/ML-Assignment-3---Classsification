ML Assignment 3 - Classification

Overview

This project applies five supervised machine-learning classification algorithms to the Breast Cancer Wisconsin Diagnostic dataset available in scikit-learn.

The objective is to train the models, evaluate their performance, and compare their classification results.

Algorithms Used

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Support Vector Machine (SVM)

k-Nearest Neighbors (k-NN)

Dataset

The dataset is loaded directly from the scikit-learn library using load_breast_cancer().

Observations: 569

Features: 30 numerical features

Target classes: Malignant and benign

Target encoding: 0 = malignant, 1 = benign

No separate dataset download is required.

Preprocessing

Check the dataset for missing values.

Use median imputation to handle any missing feature values.

Standardise features for Logistic Regression, SVM, and k-NN.

Split the data into 80% training and 20% testing sets.

Use stratification to preserve class proportions.

Use pipelines to fit preprocessing on the training data and help prevent data leakage.

Evaluation Metrics

The models are compared using:

Accuracy

Precision

Recall

F1-score

ROC-AUC

The project also generates classification reports, a model-comparison chart, and confusion matrices.

Requirements

Python 3

NumPy

pandas

Matplotlib

scikit-learn

Jupyter Notebook support (if running the .ipynb version)

How to Run in PyCharm

Download or clone this repository.

Open the project in PyCharm.

Configure a Python interpreter.

Install the required packages in the PyCharm terminal:

pip install numpy pandas matplotlib scikit-learn jupyter

Open ML_Assignment_3_Classification_Notebook.ipynb.

Select the configured Python kernel/interpreter.

Run all notebook cells from top to bottom.

You can also open the notebook in Google Colab.

Files

ML_Assignment_3_Classification_Notebook.ipynb — main assignment notebook containing the code, explanations, evaluation, visualisations, and conclusion.

README.md — project description and instructions.

Conclusion

The notebook compares the five classification algorithms using the selected test set. The best- and worst-performing models are identified based on test accuracy, while precision, recall, F1-score, ROC-AUC, and confusion matrices provide additional information about model performance.

The actual model rankings and scores should be taken from the output produced when the notebook is executed.

Disclaimer

This project is for educational purposes only. It is not intended for medical diagnosis or clinical decision-making.
