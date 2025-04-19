
---

## 🛠️ Methods Used

- **Data Cleaning & Preprocessing**
  - Missing value imputation and removal
  - Encoding categorical variables
  - Feature scaling (z-scores)

- **Exploratory Data Analysis (EDA)**
  - Histograms, boxplots, and correlation heatmaps
  - Trend analysis across seasons

- **Feature Selection**
  - Correlation analysis
  - Variance thresholding
  - Recursive Feature Elimination (RFE)

- **Modeling**
  - Classification: Logistic Regression, Random Forest, Gradient Boosting, XGBoost
  - Regression: Linear Regression, Random Forest Regression, Gradient Boosting Regression

- **Model Evaluation**
  - Classification: Accuracy, Precision, Recall, F1-score
  - Regression: MAE, RMSE

- **Hyperparameter Tuning**
  - GridSearchCV

---

## 📈 Results

- **Classification**
  - Best model: Gradient Boosting (82% accuracy)
  - Ensemble models outperformed logistic regression significantly

- **Regression**
  - Linear Regression baseline: MAE ≈ 5.4, RMSE ≈ 6.8
  - Recommended future use of non-linear models like Random Forest Regression

---

## 🔮 Future Enhancements

- Include external variables such as injuries, trades, and rest days
- Add basketball-specific metrics like PER and eFG%
- Address class imbalance using SMOTE
- Create a dashboard for real-time predictions
- Use deep learning (e.g., LSTMs) for sequence modeling
- Interpret models with SHAP values
