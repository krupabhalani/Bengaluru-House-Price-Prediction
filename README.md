# Bengaluru-House-Price-Prediction

Description: Developed a machine learning model to predict house prices in Bengaluru based on key real estate features, applying advanced preprocessing, feature engineering, and regression techniques.

Conducted data cleaning by handling missing values in location, size, bath, and balcony attributes.

Engineered features including price_per_sqft and removed outliers based on quantile analysis to enhance model stability.

Performed categorical encoding by grouping rare locations into “other” and applying OneHotEncoder within a preprocessing pipeline.

Scaled numerical data using StandardScaler and implemented models using Linear Regression, Lasso, and Ridge via make_pipeline for reproducibility.

Evaluated models using R² Score and Mean Squared Error (MSE), achieving an R² score of 0.71–0.72 on the test set.

Serialized the best-performing model using pickle for deployment readiness.

Tech Stack: Python, scikit-learn, pandas, NumPy, pickle
