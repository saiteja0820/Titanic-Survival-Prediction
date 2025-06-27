# 🚢 Titanic Survival Prediction

📎 [Open in Google Colab](https://colab.research.google.com/drive/1vye2xBsJhAwNVDGj9HiYI7C2p6XEtKKJ?usp=sharing)

This project is a classic supervised machine learning task using the Titanic dataset. The goal is to predict whether a passenger would survive the Titanic disaster based on features like age, gender, passenger class, and more.

## 🧠 Problem Statement

Using passenger data (such as age, sex, class, etc.), predict whether a passenger survived the sinking of the Titanic. This binary classification problem is one of the most well-known datasets in the data science community.

## 📊 Dataset

The dataset used is the `tested.csv` file, which includes:

- Passenger details: Name, Age, Sex, Ticket class, Fare, etc.
- Target variable: `Survived` (0 = No, 1 = Yes)

## 🔧 Tools & Libraries

- Python (pandas, numpy, matplotlib, seaborn)
- Scikit-learn
- Jupyter Notebook

## 📈 Project Workflow

### 1. Data Preprocessing
- Handled missing values (e.g., imputed age and fare with mean)
- Dropped irrelevant or high-missing columns (like `Cabin`)
- Encoded categorical variables (`Sex`, `Embarked`, etc.)
- Dropped non-informative columns like `Name`, `Ticket`, `PassengerId`

### 2. Exploratory Data Analysis (EDA)
- Visualized class distributions (e.g., survival by gender or class)
- Plotted age/fare distributions and correlations
- Identified key patterns in the dataset

### 3. Feature Engineering
- Converted categorical columns to numeric values
- Prepared features for model input

### 4. Modeling
Trained and evaluated multiple models:
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier

### 5. Evaluation Metrics
Used standard classification metrics:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## 🧪 Results

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | ~80%     |
| K-Nearest Neighbors | ~77%     |
| Decision Tree       | ~76%     |

> Logistic Regression gave the most balanced and interpretable results.
