# 🛒 Supermarket Loyalty Spending Prediction

This project was completed as part of a practice exam for the **DataCamp Data Science Associate** certification. The goal was to analyze a loyalty program dataset for a fictional international supermarket and build a model to **predict customer spending**.

---

## 📊 Project Overview

International Essentials is an international supermarket chain. Shoppers can join a loyalty program where rewards are given annually based on their total spending.

The supermarket wants to **predict customer spending** to:
- Estimate annual reward costs.
- Better forecast year-end profit margins.

---

## 🧰 Tools & Technologies

- **Python**
- **pandas** – data manipulation
- **numpy** – numerical operations
- **matplotlib** – visualizations
- **scikit-learn** – modeling (Linear Regression, Random Forest Regressor)

---

## 🔍 Steps Performed

### 1. Data Preprocessing
- Handled missing values.
- Encoded categorical features (if any).
- Normalized/standardized numerical data.

### 2. Exploratory Data Analysis (EDA)
- Visualized spending distributions.
- Analyzed feature relationships.
- Identified trends, outliers, and patterns.

### 3. Modeling
- **Linear Regression**: fast baseline model.
- **Random Forest Regressor**: handles non-linearity, better performance.

### 4. Model Evaluation
- Metrics used: **R² score**, **Mean Absolute Error (MAE)**.
- Compared both models to select the better performer.

---

## 📈 Results


> 🎯 Random Forest performed better overall with lower prediction error and captured complex relationships.

---

## 💡 Possible Improvements
- Hyperparameter tuning (e.g., GridSearchCV).
- Feature engineering (customer tenure, seasonal trends).
- Deployment via Streamlit or Flask.
- Adding cross-validation.

---

## 🗂️ Folder Structure

```bash
notebook/               # Jupyter Notebook with full analysis
images/                 # Visuals like plots and charts
data/                   # (optional) Add a note on where to get the dataset
README.md               # This file
requirements.txt        # Package dependencies
