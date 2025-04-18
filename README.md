# Final Project: Regression Analysis 📊

# Links 🔗
[My Github Repository](https://github.com/ryankrabbe/ml_regresion_krabbe)

[My Project Notebook](https://github.com/ryankrabbe/ml_regresion_krabbe/blob/main/regression_krabbe.ipynb)

[My Peer Review](https://github.com/S572396/ml-07-sruiz/blob/main/sruiz-medreg.ipynb)

---

## Project Outline

### Section 1. Import and Inspect the Data

### Section 2. Data Exploration and Preparation

### Section 3. Feature Selection and Justification

### Section 4. Train a Model (Linear Regression)

### Section 5. Improve the Model or Try Alternates (Implement Pipelines)

### Section 6. Final Thoughts & Insights

## Below is my Summary Table Template Comparing the Different Models
- This template is used to summarize my results across the different models

| Metric         | Original Linear Regression | Standard Scaler Linear Regression | Polynomial Features (Degree=3) | Notes |
|----------------|-----------------------------|-----------------------------------|----------------------------------|-------|
| **R² Score**   | 0.7836                      | 0.7836                            | 0.8486                           | Polynomial model explained more variance in charges |
| **MAE**        | $4,181.19                   | $4,181.19                         | $2,937.92                        | Polynomial model was more accurate than the Standard Scaler Linear Regression model |
| **RMSE**       | $5,796.28                   | $5,796.28                         | $4,847.50                        | Polynomial model had a lower RMSE indicating that there were fewer large prediction errors |