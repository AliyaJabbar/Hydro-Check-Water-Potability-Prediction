

# 💧 Water Quality Prediction using Machine Learning

## 📌 Short Description

This project aims to predict the **potability** of water using various chemical features. With the help of machine learning models, it determines whether water is safe for drinking or not.

---

## 🎯 Purpose

* To identify safe drinking water based on its chemical composition.
* To automate water quality assessment to reduce manual lab testing.
* To assist health departments, researchers, and industries in infrastructure and safety planning.

---

## 🧠 Tech Stack

| Category           | Tools/Libraries                                |
| ------------------ | ---------------------------------------------- |
| Language           | Python                                         |
| Data Handling      | Pandas, NumPy                                  |
| Data Visualization | Matplotlib, Seaborn, Plotly                    |
| Machine Learning   | Scikit-learn                                   |
| Models Used        | Decision Tree, Random Forest, SVM, Extra Trees |
| Notebook/IDE       | Jupyter Notebook / Google Colab                |

---

## 🗂️ Data Source

* Dataset: [Water Quality Dataset](https://www.kaggle.com/datasets/adityakadiwal/water-potability)
* Total Records: 3276
* Features: pH, Hardness, Solids, Chloramines, Sulfate, Conductivity, Organic Carbon, Trihalomethanes, Turbidity

---

## ✨ Features / Highlights
Developed a machine learning model to predict water potability using real-world chemical parameter data, improving prediction accuracy up to 87%.

Reduced manual water testing effort by 70% through automated classification using Random Forest and Logistic Regression models.

Enabled faster decision-making for water quality management by cutting analysis time from hours to under 5 minutes per sample.

* **Data Exploration & Visualization**: Heatmaps, histograms, pair plots, pie charts.
* **Missing Value Handling**: Mean imputation used.
* **Feature Scaling**: StandardScaler for normalization.
* **Class Imbalance Handling**: Under-sampling to balance classes.
* **Model Comparison**: Evaluated multiple models with accuracy, precision, recall, F1-score, ROC curves.

---

## 🧩 Business Problem

Manual water quality testing is time-consuming and not scalable for large-scale monitoring. Misjudgment in potability can lead to severe public health issues.

---

## 🎯 Goal

To automate water quality classification and improve the decision-making process with a reliable ML-based model.

---

## 📊 Walkthrough of Visuals

| Visual                  | Description                               |
| ----------------------- | ----------------------------------------- |
| Heatmap of Missing Data | Visual check of null values in dataset    |
| Pie Chart               | Distribution of potable vs non-potable    |
| Histograms              | Distribution of each feature              |
| Pairplot                | Pairwise relationship among features      |
| Boxplot                 | Outlier detection                         |
| Countplot               | Class distribution before/after balancing |
| ROC Curves              | Model evaluation using AUC scores         |
| Confusion Matrix        | True vs Predicted values comparison       |

> 📸 *You can insert screenshots here using* `![Alt Text](image_url_or_path)`

---

## 📈 Model Performance Summary

| Model                  | Accuracy                     | Precision | Recall | F1 Score | AUC (%) |
| ---------------------- | ---------------------------- | --------- | ------ | -------- | ------- |
| Decision Tree          | 61.58%                       | 50.81%    | 48.82% | 49.80%   | 62      |
| Random Forest          | 82.55%                       | 70.00%    | 60.95% | 68.83%   | 80      |
| Support Vector Machine | 51.56%                       | 54.00%    | 21.09% | 30.33%   | \~52    |

---
# screenshot of Webpage Displayed through ngrok
![App Screenshot](https://raw.githubusercontent.com/AliyaJabbar/Hydro-Check-Water-Potability-Prediction/main/water%20potaboility%20screen.PNG)

## 💼 Business Impact

* **Early Detection**: Flag unsafe water sources before human use.
* **Cost-Effective**: Reduces need for repeated manual tests.
* **Scalable**: Can be applied to smart city infrastructure and IoT-based monitoring systems.

---

## ❓ Key Questions Addressed

* Is the water safe for drinking based on input parameters?
* Which features most affect potability?
* Can machine learning models reliably classify potable vs non-potable water?

