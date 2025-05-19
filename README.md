# Loan Default Prediction
Predictive modeling project using R to identify high-return and low-risk P2P loans. Applied decision trees, random forests, and XGBoost to forecast defaults and returns, enabling smarter investment strategies based on profit optimization and risk assessment.

## 🧠 Objective

- Predict whether a loan will be **fully paid** or **charged off**
- Estimate the **annualized return** of each loan
- Develop investment strategies to **maximize profit** and **minimize risk**

## 🗂️ Files

- `Assignment 2_IDS 572.rmd`: R Markdown code for data cleaning, exploration, modeling, and evaluation
- `Assignment 2_IDS 572 Part A+B.pdf`: Final report summarizing analysis and results

## 🔧 Methodology

- **Data Cleaning**: Handled missing values, removed post-loan variables to prevent leakage
- **Feature Engineering**: Created derived variables like loan-to-income ratio, inquiry rate
- **Modeling Techniques**:
  - Decision Tree (rpart)
  - Random Forest (ranger)
  - XGBoost (xgbTree and xgboost)
- **Evaluation Metrics**:
  - Classification: Accuracy, AUC, ROC, Confusion Matrix
  - Regression: RMSE, R² for return prediction
  - Business impact: Profit simulation from $100 loan investments

## 💰 Investment Strategy

- Combined model predictions to filter low-risk loans and rank by expected return
- Evaluated strategies like:
  - Filter then Rank
  - Weighted Scoring (60% risk, 40% return)
- Compared performance vs. fixed-return investments (e.g., CDs)

## 📈 Key Results

- **Best Model**: XGBoost for both default prediction (AUC = 0.979) and return prediction
- **Highest Simulated Profit**: $826,551.60 using XGBoost with optimal threshold
- **Recommendation**: Use combined model strategy for balanced risk-return decisions

## 👩‍💻 Authors

- Debangana Sanyal 

## 📚 Tools & Libraries

- R, rpart, ranger, xgboost, caret, ggplot2, dplyr

---

*Built for IDS 572 – Data Mining for Business Analytics*

