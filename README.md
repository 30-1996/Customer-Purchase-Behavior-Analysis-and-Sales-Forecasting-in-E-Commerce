
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
- Removed outliers using Z-score analysis
- Visualized distributions and correlations

### 🧠 Machine Learning Models

The following algorithms were trained and evaluated:

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest Classifier
- Gradient Boosting Classifier

### 🧪 Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Cross-validation
- Hyperparameter Tuning (Grid Search / Randomized Search)

## 📈 Results

| Model                  | Accuracy | F1 Score |
|------------------------|----------|----------|
| Logistic Regression    | ~0.87    | 0.87     |
| Gradient Boosting      | ~0.89    | **0.89** |
| Random Forest          | -        | -        |
| SVM                    | -        | -        |

> 📌 *Gradient Boosting showed the best overall performance in terms of F1 Score.*

## 📁 Project Structure

```
Customer-Purchase-Behavior-Analysis-and-Sales-Forecasting/
├── data/
│   └── online_shoppers_intention.csv
├── notebooks/
│   ├── preprocessing_and_EDA.ipynb
│   ├── model_training.ipynb
│   └── results_analysis.ipynb
├── results/
│   └── confusion_matrices/
│   └── evaluation_reports/
├── README.md
```

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Customer-Purchase-Behavior-Analysis-and-Sales-Forecasting.git
   cd Customer-Purchase-Behavior-Analysis-and-Sales-Forecasting
   ```

2. Install dependencies (optional, if you provide `requirements.txt`):
   ```bash
   pip install -r requirements.txt
   ```

3. Open Jupyter Notebook and run through the notebooks in order.

## 📌 Future Work

- Feature engineering based on temporal patterns
- Ensemble learning and stacking models
- Integration with a live dashboard

## 🧑‍💻 Author

Noumida A.  
Ph.D. Researcher in Machine Learning and Speech Technology  
[LinkedIn](#) | [Email](#)

---

⭐ If you found this project helpful, feel free to star the repo!
