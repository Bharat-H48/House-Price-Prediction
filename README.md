# House Price Prediction

1. Project Overview
- This project applies **Linear Regression** with Python’s Scikit-learn to predict U.S. house prices.  
- The goal is to build a fast, reliable, and data-driven alternative to traditional property appraisal methods.

2. Data Preparation
- Raw dataset: 5,000 property records with 7 core features (Income, Age, Rooms, etc.).
- Cleaned non-numerical data and checked feature correlations.
- Prepared independent variables (X) and target variable (y).
- Applied an 80/20 train-test split for robust validation.

3. Model Implementation
- Algorithm: **Linear Regression** (Scikit-learn).
- Key predictors: `Avg. Area Income` and `Avg. Area House Age`.
- Performance: Achieved low RMSE of **$102,278**.
- Error distribution: Near-normal, confirming unbiased and reliable predictions.

4. Insights & Recommendations
- **Valuation Insight:** Low RMSE validates the model’s reliability for rapid, high-volume property valuation.
- **Growth Opportunity:** Area Population is a growing factor, especially in urbanizing regions.
- **Strategic Advice:** Use this model for pre-screening investment properties to reduce financial risk.

5. Tech Stack
- Python  
- Pandas & NumPy  
- Scikit-learn (Linear Regression)  
- Matplotlib & Seaborn  
