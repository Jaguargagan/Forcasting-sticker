# Forcasting Sticker Project

## Overview
This project focuses on building and evaluating regression models to predict outcomes accurately. The key objective is to analyze model performance using various metrics and visualizations, such as residuals distribution, feature importance, and actual vs. predicted values.

## Key Features
1. **Model Evaluation:**
   - Models like Linear Regression, Random Forest, Gradient Boosting, and XGBoost were trained and compared.
   - XGBoost achieved the best performance with the lowest RMSE of 0.10.

2. **Visualizations:**
   - **Residuals Distribution:** Showcasing errors (actual - predicted) are centered around 0, indicating unbiased predictions.
   - **Feature Importance:** Highlighting the most influential features in the model, with `country`, `year`, and `month` being the top contributors.
   - **Actual vs. Predicted Plot:** Comparing predicted values to actual values, showing strong alignment with minimal errors.

3. **Performance Metrics:**
   - Root Mean Square Error (RMSE) used to measure prediction accuracy.
   - Residuals analysis confirms normal distribution of errors.

## Key Insights
- The XGBoost model demonstrated strong predictive accuracy and robustness.
- Seasonal and regional factors (e.g., country, year, month) play a significant role in the predictions.
- Visualizations provide clear evidence of the model's reliability and areas for improvement.
