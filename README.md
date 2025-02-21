# Heart-Disease-Prediction-using-ML-models
# 🧠 Machine Learning Model Accuracy Comparison

This project evaluates and compares the performance of multiple machine learning models using a dataset. The goal is to analyze model accuracy and visualize the results to determine the best-performing algorithm.

## 📌 Objectives
- Implement and compare different machine learning models.
- Train models on a dataset and evaluate their accuracy.
- Visualize model performance using a bar chart.

## 📂 Dataset
The dataset used contains multiple features and a target variable for classification.  
Key features include:
- **Independent variables** (various attributes influencing prediction).
- **Target variable** (0: Negative, 1: Positive).

### Dataset Exploration:
- **Shape:** *X* rows and *Y* columns.
- **Missing Values:** Checked and handled (if applicable).
- **Feature Types:** Numerical and categorical variables.

## 📊 Exploratory Data Analysis (EDA)
- **Feature Correlation Heatmap** to understand relationships.
- **Histograms & Boxplots** for feature distributions.
- **Pairplot** to visualize feature relationships.

## 🏗️ Data Preprocessing
- **Feature Selection:** Extracted key features.
- **Train-Test Split:** Data divided (80% train, 20% test).
- **Feature Scaling:** Standardized features using `StandardScaler`.

## 🛠️ Models Implemented
The following machine learning models were trained and tested:
- **Logistic Regression**
- **Random Forest Classifier**
- **Support Vector Machine (SVM)**
- **Decision Tree**
- **K-Nearest Neighbors (KNN)**

## 📈 Results

| Model                 | Accuracy (%) |
|----------------------|-------------|
| Logistic Regression | 85%         |
| Random Forest       | 84%         |
| SVM                | 87%         |
| Decision Tree      | 75%         |
| K-Nearest Neighbors | 90%        |

## 🎨 Model Accuracy Visualization
A **bar chart** was generated to compare model accuracies.
[Model Accuracy](accuracy_comparison.png)


```bash
python model_accuracy.py
