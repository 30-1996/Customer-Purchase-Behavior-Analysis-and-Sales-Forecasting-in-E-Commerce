
# 🛒 Customer Purchase Behavior Analysis and Sales Forecasting in E-Commerce

This project analyzes behavioral data from an e-commerce platform to **predict whether a session will lead to a purchase** (`Revenue = 1`). Multiple machine learning algorithms are applied to model customer intent based on session attributes like page interactions, traffic source, visitor type, and more.

## 📊 Dataset

- **Source**: [UCI Machine Learning Repository – Online Shoppers Purchasing Intention Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset)
- **Records**: 12,330
- **Features**:
  - Session duration metrics
  - Page value, bounce rates
  - Month, weekend
  - Visitor type (Returning/Guest)
  - Operating system, traffic source, etc.

## 🔧 Key Steps in the Project

### ✅ Data Preprocessing

- Handled missing and malformed values
- Encoded categorical features using one-hot encoding

### 🧠 Machine Learning Models

The following algorithms were trained and evaluated:

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest Classifier
- Gradient Boosting Classifier

### 🧪 Evaluation Metrics

Models were evaluated using:

- Precision
- Recall
- F1 Score
- Confusion Matrix

## 📈 Results

| Model                   | F1 Score |
|------------------------ |----------|
| Logistic Regression     |   0.87   |
| Gradient Boosting       | **0.89** |
| Random Forest           | **0.89** |
| SVM                     |  0.88    |

> 📌 *Gradient Boosting and Random Forest showed the best overall performance in terms of F1 Score.*

## 📁 Project Structure

```
Customer-Purchase-Behavior-Analysis-and-Sales-Forecasting/
├── data/
│   └── online_shoppers_intention.csv
├── notebooks/
│   ├── online_shoppers_intention.ipynb
├── results/
│   └── confusion_matrices/
│   └── evaluation_reports/
├── README.md
```

