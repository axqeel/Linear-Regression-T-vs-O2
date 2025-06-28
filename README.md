# Linear-Regression-T-vs-O2

This repository contains a **Linear Regression analysis** using Python and `scikit-learn` to establish **how water temperature affects dissolved oxygen levels** using **LOIS continuous monitoring data**.

---

## 🤖 What is Linear Regression?

**Linear Regression** is a fundamental supervised machine learning algorithm used to:
- Model the relationship between an independent variable (feature) and a dependent variable (target).
- Predict continuous outcomes based on input features.

In this project:
- **Feature (`X`)**: Water temperature.
- **Target (`y`)**: Dissolved oxygen levels.

---

## 🚀 Features

✅ Loads **LOIS continuous dataset**.  
✅ Filters data for:
- **SITE_NAME = "Swale at Catterick Bridge"**.

✅ Drops irrelevant columns (`FID`, `ID`, `SITE_NAME`, `DATE`).  
✅ Handles missing data by removing incomplete rows.  
✅ Fits **Linear Regression** to analyze:
- The relationship between **water temperature and dissolved oxygen levels**.

✅ Computes:
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**

to evaluate model performance.

---

## 🗂️ Dataset

The **LOIS (Land-Ocean Interaction Study) continuous dataset** contains:
- Water quality parameters across various sites and dates.
- Columns used:
  - **`Temperature water continuous`** (°C)
  - **`Oxygen dissolved continuous`** (% saturation)

---

## 🛠️ Dependencies

- Python 3.x
- pandas
- numpy
- scikit-learn

Install dependencies using:

```bash
pip install pandas numpy scikit-learn
