# Predictive-Analysis-of-Healthcare-Premiums-using-AI-ML

This project analyzes healthcare insurance premium variations across the U.S. based on metal levels, plan types (HMO/PPO), and geographic factors using predictive models. It highlights disparities and uses machine learning to predict premiums, providing insights for consumers, insurers, and policymakers.


## 🔍 Problem Statement
Healthcare insurance plans in the U.S. vary widely by region, plan type, and coverage tier, making it difficult for consumers to choose affordable options. This project identifies cost-driving features and predicts healthcare premiums to improve transparency and guide decision-making.


## 🛠 Tools Used
- **Python** (pandas, NumPy, matplotlib, seaborn, scikit-learn)
- **Machine Learning**: Random Forest, XGBoost, K-Nearest Neighbors
- **Statistical Tests**: ANOVA, Correlation Matrix
- **Data Source**: [healthcare.gov](https://data.healthcare.gov)


## ⚙️ Key Features / Methods
- **Exploratory Data Analysis (EDA)**: Distributions by metal level, state, and plan type
- **Feature Engineering**: Median imputation for missing data, log transformation for normality
- **Outlier Removal**: IQR-based filtering
- **Predictive Modeling**:
  - Random Forest (R² = 0.90)
  - XGBoost (R² = 0.76)
  - KNN (R² = 0.73)
- **Statistical Validation**: ANOVA for regional significance


## 📈 Outcome / Impact
- Platinum & PPO plans are highest in cost; Bronze & HMO are more affordable.
- Clear regional disparities — e.g., Virginia shows significantly higher premiums.
- Random Forest model explains 90% of premium variation, aiding accurate prediction.
