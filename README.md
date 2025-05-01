# Task 4 - Logistic Regression (Breast Cancer Classification)

## 🎯 Objective
Build a logistic regression model to classify breast cancer tumors as malignant (1) or benign (0).

## 🛠️ Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## 📁 Dataset
- File: `data.csv`
- Source: [Breast Cancer Wisconsin Dataset on Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

## 📚 Steps Performed
1. Loaded dataset using Pandas
2. Dropped unnecessary columns (`Unnamed: 32`, `id`)
3. Encoded target column (`diagnosis`)
4. Scaled input features
5. Trained Logistic Regression model
6. Evaluated model using:
   - Classification Report
   - Confusion Matrix
   - ROC-AUC Score
   - ROC Curve

## 📈 Sample Output

✅ Dataset loaded!

📊 Classification Report: precision recall f1-score support 0 0.97 0.99 0.98 71 1 0.98 0.95 0.96 43

accuracy 0.97 114 ROC-AUC Score: 1.00

📉 Confusion Matrix: [[70 1] [ 2 41]]

## ▶️ How to Run

```bash
pip install pandas scikit-learn matplotlib seaborn
python task4.py


