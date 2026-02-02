🏠 Housing Price Prediction  

Regression Modeling & Residual Diagnostics

  This project presents an end-to-end regression workflow for predicting housing prices, with a strong emphasis not only on model performance but also on validating regression assumptions through residual diagnostics.
    
  Rather than stopping at evaluation metrics, this project demonstrates how diagnostic plots can reveal underfitting, non-linearity, and heteroscedasticity, leading to better modeling decisions.

📌 Project Objectives

  - Build a baseline Linear Regression model for housing price prediction
  - Examine feature–target relationships through Exploratory Data Analysis (EDA)
  - Validate linear regression assumptions
  - Identify model limitations using residual diagnostics
  - Improve model quality using target variable transformation

🔧 Workflow Overview

1. Exploratory Data Analysis (EDA)
   - Distribution analysis of numerical features
   - Feature–target relationship visualization
   - Skewness detection in the target variable

2. Data Preprocessing
   - One-Hot Encoding for categorical variables
   - Train–test split
   - Feature scaling (where required)

3. Baseline Model
   - Linear Regression using `scikit-learn`
   - Model trained on original target values

4. Model Evaluation
   - R² Score
   - Mean Absolute Percentage Error (MAPE)

5. Residual Diagnostics
   - Residuals vs Predicted Values
   - Residual distribution analysis
   - Actual vs Predicted plots
   - Detection of:
     - Non-linearity
     - Heteroscedasticity
     - Underfitting

6. Target Transformation
   - Log transformation applied to the target variable
   - Improved variance stability and residual behavior

7. Post-Transformation Evaluation
   - Re-trained model
   - Re-evaluated metrics
   - Improved residual patterns


📊 Key Insights

- Residual plots revealed systematic patterns, indicating that:
  - The baseline linear model was underfitting
  - The relationship between features and target was partly non-linear
- Log transformation of the target variable:
    - Reduced skewness
    - Stabilized variance
    - Improved residual distribution
- This reinforced the importance of residual analysis alongside standard metrics like R² and MAPE

---

🛠 Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
