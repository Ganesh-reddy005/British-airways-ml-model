# ✈️ British Airways Predictive Model

A data-driven modeling project that explores flight eligibility and tier access at Heathrow Terminal 3, using Python-based predictive techniques.

## 🚀 Objective

To analyze flight data and estimate **lounge eligibility percentages** using predictive modeling techniques like decision trees and XGBoost. The goal is to group flights and derive insights that support tiered lounge access planning.

## 🧠 Features

- 🔍 Data preprocessing with `pandas` and `numpy`
- 📈 Predictive modeling using `XGBoost`, `RandomForest`, and `DecisionTreeClassifier`
- 📊 Visualization and performance metrics
- ⚙️ Modular code structure with configurable pipelines
- 🛫 Domain logic specific to Heathrow Terminal 3 lounge access

## 🛠️ Tech Stack

| Component            | Tools/Libraries                    |
|---------------------|-------------------------------------|
| Programming Language | Python 🐍                          |
| ML Models            | XGBoost, Random Forest, Decision Tree |
| Visualization        | matplotlib, seaborn                 |
| Version Control      | Git + GitHub                        |

## Model Overview
- Model Used: Random Forest Classifier
- Parameters: n_estimators=200, max_depth=20, min_samples_split=5, random_state=42
- Training Accuracy: 89.9%
- Test Accuracy: 84.9%
Made sure that model is not over trained on Training Data and performs well on Unseen data.


## 🧪 Setup & Installation
```bash
git clone git@github.com:Ganesh-reddy005/British-airways-predictive-model.git
cd British-airways-predictive-model
pip install -r requirements.txt
