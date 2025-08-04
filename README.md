Red Wine Quality Classification

This project applies supervised machine learning techniques to classify the quality of red wine based on various physicochemical properties.

It includes:
- Data loading and preprocessing
- Exploratory Data Analysis (EDA)
- Feature selection
- Model training using classification algorithms
- Model evaluation (accuracy, confusion matrix, etc.)

Dataset

The dataset used is the **Red Wine Quality dataset** from the UCI Machine Learning Repository:
It contains physicochemical attributes of red wine samples and a quality score (0–10). For this project, the quality scores are converted into classification labels.

Features Used

Some of the features include:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol

ML Techniques Used

- Data normalization and label encoding
- Train-test splitting
- Logistic Regression
- Random Forest Classifier
- SVC
- Evaluation metrics like Accuracy, Classification Report, Confusion Matrix

Results

The models are evaluated based on their performance in classifying wine quality into discrete categories. The notebook includes comparison results for multiple models.

Requirements

To run the notebook, install the following packages (e.g., via pip):


pip install pandas numpy matplotlib seaborn scikit-learn
