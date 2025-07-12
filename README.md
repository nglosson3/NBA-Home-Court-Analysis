# 🏀 NBA Home Court Advantage Analysis (1946–2023)

Using data from over 25,000 NBA games spanning 75+ years, this project investigates the impact of **home court advantage** on team performance. It explores scoring trends, win probabilities, and uses statistical and machine learning models to predict both point differentials and game outcomes.

---

## 📌 Project Objectives

- Analyze whether home teams have a measurable advantage
- Visualize scoring and shooting trends across decades
- Predict **margin of victory** using linear regression
- Predict **home team win** (binary outcome) using classification models (Logistic and Random Forest)

---

## 🧰 Tools & Libraries

- **Python**: pandas, numpy, matplotlib, seaborn
- **Modeling**: statsmodels, scikit-learn (OLS, Logistic Regression, Random Forest)
- **Data Visualization**: seaborn, matplotlib
- **Data Source**: 25,000+ NBA games from regular season and playoffs


---

## 📊 Key Insights

- **Home teams win ~60.5%** of games across history
- Average **margin of victory** at home is positive (~3.2 points)
- Home teams generally outperform away teams in FG%, REB, and AST
- **Regression model (OLS)** explains ~37% of variance in point differential  
- **Random Forest Classifier** achieves:
  - **Accuracy**: ~89%
  - **ROC AUC**: ~0.96

---

## 📈 Visual Highlights

### Home Win % Over Time (Excluding 1960 due to Incomplete Data)
<img width="450" height="350" alt="Home_win" src="https://github.com/user-attachments/assets/dbf8d721-d8d9-4e70-995a-c553e6e44a34" />

### Logistic Regression ROC Curve

<img width="450" height="350" alt="ROC_Curve" src="https://github.com/user-attachments/assets/eae3f5f4-ff9a-4476-840e-173837b70a33" />

---

## 📌 Room for Improvement

- Include team strength metrics (Elo ratings, standings)
- Compare pre-COVID vs. post-COVID era
- Test more advanced models (XGBoost, SHAP explanations)

---
