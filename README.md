# 🧠 Tweet Sentiment Classification: PySpark vs Python

This project aims to classify tweet sentiments (positive, negative, neutral) using machine learning and compare the performance of models built with **Apache PySpark** using docker and **Python (scikit-learn)**.

---

## 🔍 Project Objectives

- Load and preprocess real-world tweet datasets.
- Build and train sentiment classification models.
- Evaluate model performance using metrics like accuracy.
- Compare the speed and accuracy of:
  - **PySpark MLlib** (distributed processing)
  - **Python scikit-learn** (single-node)

---

## 🗂️ Datasets Used

- **Airline Tweet Sentiment Dataset**
- **General Tweet Sentiment Dataset**

Each dataset contains tweets labeled with sentiment classes. The data is split into:
- 80% Training
- 20% Testing

---

## ⚙️ Models Implemented

### PySpark MLlib:
- Logistic Regression
- Naive Bayes
- Decision Tree
- Random Forest
- One-vs-Rest with Linear SVM

### Python (scikit-learn):
- Logistic Regression
- Multinomial Naive Bayes
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

---

## 🧪 Evaluation Metric

- **Accuracy**
- Tested on unseen test datasets for fair comparison.

---

## 📊 Results Summary

| Model           | PySpark Accuracy | Python Accuracy |
|-----------------|-------------------|------------------|
| Decision Tree   | 83%              | 54%             |
| Random Forest   | 84%              | 84%             |
| SVM (OvR)       | 86%              | 76%             |

---
## 📄 License

This project is licensed under the [MIT License](LICENSE).

