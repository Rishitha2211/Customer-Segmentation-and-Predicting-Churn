# Customer Segmentation & Churn Prediction 

## 📌 Project Overview

This project aims to segment e-commerce customers based on their behavior and predict their churn probability using clustering and classification techniques.

## 📊 Key Statistical Concepts Used

- **Descriptive Statistics & Correlation Analysis**
- **Dimensionality Reduction**: PCA, t-SNE
- **Clustering**: K-Means (faiss), Gaussian Mixture Model (GMM)
- **Predictive Modeling**: Logistic Regression, Random Forest
- **Model Evaluation**: Confusion Matrix

## 🔗 Dataset

- **Source**: [E-Commerce Customer Churn Analysis Dataset](https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction/data)


## 📌 Steps Followed

### 1️⃣ Data Preprocessing
- Handled missing values using **Iterative Imputer**.
- Standardized numerical features using **Standard Scaler**.

### 2️⃣ Exploratory Data Analysis (EDA)
- Performed **univariate** and **bivariate** analysis.
- Visualized missing values using **missingno**.

### 3️⃣ Customer Segmentation
- Applied **Faiss K-Means** for efficient clustering.
- Used **Gaussian Mixture Model (GMM)** for probabilistic clustering.
- Evaluated clusters using **Silhouette Score** and **Calinski-Harabasz Score**.

### 4️⃣ Churn Prediction Model
- Trained **Logistic Regression** and **Random Forest** classifiers.


### 5️⃣ Model Evaluation
- Assessed performance with **confusion matrix** 


## 🚀 Results
| Model                 | Accuracy |
|----------------------|----------|
| Logistic Regression  | 84%      |
| Random Forest       | 96%      |

## 🔧 Improvements to be made
- More data visualization
- Implement XGBoost for better performance.
- Hyper parametertune Random Forest for optimal parameters.

## 📂 Project Structure
- Customer_Clustering_and_Churn_Prediction.py: code file
- Churn_predictions_gmm.csv: predictions

