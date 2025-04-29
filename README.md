# Logistic-Regression-Data
1.Choose a binary classification dataset.  2.Train/test split and standardize features.  3.Fit a Logistic Regression model.  4.Evaluate with confusion matrix, precision, reca l, ROC-AUC.  5.Tune threshold and explain sigmoid function.
# Task 4: Logistic Regression – Breast Cancer Classification

This project demonstrates binary classification using **Logistic Regression** on the **Breast Cancer Wisconsin Dataset**.

---

## 📁 Dataset

- **Source**: [Breast Cancer Wisconsin Dataset (UCI)](https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic))
- **File**: `data.csv`
- **Target**: `diagnosis` (Malignant = 1, Benign = 0)

---

## 🔧 Steps Performed

1. Imported dataset and performed preprocessing:
   - Removed unnecessary columns (`id`, `Unnamed: 32`)
   - Converted target labels from 'M' and 'B' to 1 and 0
2. Split data into training and testing sets
3. Applied feature scaling using `StandardScaler`
4. Trained a Logistic Regression model using `sklearn`
5. Evaluated the model using:
   - Confusion Matrix
   - Classification Report
   - ROC-AUC Score
   - ROC Curve
6. Performed threshold tuning (example: 0.3)

---

## 🧪 Model Evaluation Metrics

- **Confusion Matrix**: Measures TP, FP, FN, TN
- **Classification Report**: Shows precision, recall, F1-score
- **ROC-AUC Score**: Measures model’s ability to distinguish between classes
- **ROC Curve**: Visual representation of trade-off between sensitivity and specificity

---

## 📦 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn` (model training, metrics, preprocessing)

---

## 💡 Interview Tips

- **Why use logistic regression over linear regression?**
- **What is ROC-AUC and how do you interpret it?**
- **How does changing the threshold affect precision/recall?**
- **What assumptions does logistic regression make?**
- **What are the limitations of logistic regression?**

---

## 🚀 Usage

To run the project:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
python logistic_regression_breast_cancer.py
