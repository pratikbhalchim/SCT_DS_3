# 🌳 Decision Tree Classifier – Bank Marketing Dataset

## 📌 Project Overview

This project builds a **Decision Tree Classification model** to predict whether a customer will **purchase a bank product (term deposit)** based on their **demographic and behavioral data**.

The dataset used is the **Bank Marketing Dataset** from the **UCI Machine Learning Repository**, which contains real-world marketing campaign data from a Portuguese banking institution.

---

## 🎯 Problem Statement

To predict customer subscription (`yes` / `no`) to a term deposit using historical marketing data, helping banks:

* Improve campaign targeting
* Reduce marketing costs
* Increase conversion rates

---

## 📊 Dataset Information

* **Source:** UCI Machine Learning Repository
* **Dataset Name:** Bank Marketing Dataset
* **Records:** 45,211
* **Features:** 16 input features
* **Target Variable:** `y` (customer subscribed or not)

### 🔑 Key Features

* Demographic: `age`, `job`, `marital`, `education`
* Behavioral: `contact`, `duration`, `campaign`, `previous`
* Economic indicators: `emp.var.rate`, `cons.price.idx`

---

## 🛠️ Technologies Used

* **Python**
* **Pandas & NumPy**
* **Scikit-learn**
* **Matplotlib**
* **Seaborn**

---

## 🔁 Project Workflow

1. Data Loading
2. Data Cleaning & Encoding
3. Feature Selection
4. Train-Test Split
5. Decision Tree Model Training
6. Model Evaluation
7. Decision Tree Visualization

---

## 🧪 Model Implementation

### Decision Tree Classifier

* **Criterion:** Gini Index
* **Max Depth:** 5
* **Train-Test Split:** 80% / 20%

```python
DecisionTreeClassifier(criterion='gini', max_depth=5, random_state=42)
```

---

## 📈 Model Evaluation

### Metrics Used:

* Accuracy Score
* Precision, Recall, F1-score
* Confusion Matrix

### ✅ Results (Approx.)

* **Accuracy:** 85–90%
* Strong interpretability
* Effective for marketing decision analysis

---

## 🧠 Key Insights

* **Call duration** is the most influential factor in predicting subscription
* Customers with **previous positive outcomes** are more likely to subscribe
* Decision Trees provide **clear business rules** for decision-making

---

## 📂 Project Structure

```
├── data/
│   └── bank-full.csv
├── notebook/
│   └── decision_tree_bank_marketing.ipynb
├── images/
│   └── decision_tree_visualization.png
├── README.md
```

---

## 🚀 How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/your-username/bank-marketing-decision-tree.git
```

2. Install dependencies

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

3. Run the notebook or Python script

---

## 📌 Conclusion

This project demonstrates how **Decision Tree models** can effectively analyze customer behavior and support **data-driven marketing strategies** in the banking sector.

