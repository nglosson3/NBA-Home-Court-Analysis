# 🏀 NBA Home Court Advantage Analysis (1946–2023)

Using data from over 25,000 NBA games spanning 75+ years, this project investigates the impact of **home court advantage** on team performance. It explores scoring trends, win probabilities, and uses statistical and machine learning models to predict both point differentials and game outcomes.

---

## 📌 Project Objectives

- Analyze whether home teams have a measurable advantage
- Visualize scoring and shooting trends across decades
- Predict **margin of victory** using linear regression
- Predict **home team win** (binary outcome) using classification models

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
<img width="448" height="453" alt="ROC_Curve" src="https://github.com/user-attachments/assets/d2a74594-3be7-46a8-85dc-fbbe45fec771" />

### Home Win % Over Time
![home_win_trend](outputs/home_win_trend_plot.png)

### Logistic Regression ROC Curve
![roc_logistic](outputs/roc_curve_logistic.png)

---

## 📌 Future Improvements

- Include team strength metrics (Elo ratings, standings)
- Compare pre-COVID vs. post-COVID era
- Test more advanced models (XGBoost, SHAP explanations)

---
