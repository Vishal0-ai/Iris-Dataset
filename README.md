# 🌸 Iris Flower Classification | Machine Learning

A Machine Learning classification project that uses the **Iris dataset** to classify flowers into three different species: **Setosa, Versicolor, and Virginica**.

The project demonstrates an end-to-end **supervised learning workflow**, including data preparation, feature selection, train-test splitting, model training, and prediction using a **Random Forest Classifier**.

---

## 📌 Project Overview

The objective of this project is to build a Machine Learning model that can predict the species of an Iris flower based on its physical measurements.

The dataset contains:

- **150 flower samples**
- **3 target classes**
- **4 numerical features**

### Target Classes

- 🌱 Setosa
- 🌸 Versicolor
- 🌺 Virginica

---

## 🔄 Machine Learning Workflow

```text
Iris Dataset
     ↓
Data Loading
     ↓
Data Inspection
     ↓
Feature Selection
     ↓
Train / Test Split
     ↓
Random Forest Model
     ↓
Model Training
     ↓
Prediction
     ↓
Model Evaluation

📊 Dataset

The project uses the classic Iris Flower Dataset.

Features
Feature	Description
Sepal Length	Length of the sepal
Sepal Width	Width of the sepal
Petal Length	Length of the petal
Petal Width	Width of the petal
Target

The target variable represents the flower species:

Class	Species
0	Setosa
1	Versicolor
2	Virginica
🛠️ Tech Stack
Python
Pandas
NumPy
Scikit-learn
Random Forest
Jupyter Notebook
Machine Learning
🧹 Data Preparation

The dataset was prepared before training the Machine Learning model.

Steps
Loaded the Iris dataset
Inspected the dataset structure
Selected the four numerical features
Defined the target variable
Separated features and target
Split the dataset into training and testing sets

Example:
from sklearn.model_selection import train_test_split

X_train, X_test, y_train, y_test = train_test_split(
    X,
    y,
    test_size=0.2,
    random_state=42
)
🌲 Random Forest Classification

A Random Forest Classifier was used to classify the Iris flowers.

Random Forest is an ensemble Machine Learning algorithm that combines multiple decision trees to make predictions.

Model Implementation
from sklearn.ensemble import RandomForestClassifier

model = RandomForestClassifier(
    n_estimators=100,
    random_state=42
)

model.fit(X_train, y_train)
🔮 Prediction

After training, the model was used to predict the classes of unseen test data.
y_pred = model.predict(X_test)
The predictions were then compared with the actual target values to evaluate the classification model.

📏 Model Evaluation

The model can be evaluated using classification metrics such as:

Accuracy
Precision
Recall
F1 Score
Confusion Matrix

Example:
from sklearn.metrics import accuracy_score, classification_report

accuracy = accuracy_score(y_test, y_pred)

print("Accuracy:", accuracy)
print(classification_report(y_test, y_pred))
🧠 Key Concepts Demonstrated

This project demonstrates practical understanding of:

Supervised Learning
Classification
Feature Selection
Train-Test Split
Random Forest
Model Training
Model Prediction
Classification Metrics
Scikit-learn
Python Data Handling

🚀 Future Improvements

Potential improvements include:

Comparing Random Forest with other classification algorithms
Hyperparameter tuning
Cross-validation
Feature importance analysis
Confusion matrix visualization
Interactive prediction interface
Model deployment using Streamlit or Flask
👤 Author
Vishal Yadav

Aspiring Data Analyst | Python | SQL | Power BI | Machine Learning

🔗 Skills

Python Pandas NumPy Scikit-learn Random Forest Machine Learning Classification Data Analysis
