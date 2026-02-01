# Predicting-Health-Insurance-Cost

This project predicts medical insurance costs based on personal attributes such as age, gender, BMI, smoking habits, and region. It leverages machine learning models to analyze patterns in health and lifestyle data, providing accurate cost estimations.
The goal is to demonstrate end-to-end ML workflow skills: data preprocessing, model training, evaluation, and deployment via a simple app interface.

# Features
- Exploratory Data Analysis (EDA): Visualizations of key features (age, BMI, smoking status).
- Preprocessing: Handling categorical variables, normalization, and train-test split.
- Modeling: Multiple regression models (Linear Regression, Random Forest, XGBoost).
- Evaluation: Metrics like MAE, RMSE, and R² score.

# Dataset
- Source: Medical Cost Personal Dataset (commonly available on Kaggle).
- Features:
- Age (numeric)
- Sex (male/female)
- BMI (numeric)
- Children (number of dependents)
- Smoker (yes/no)
- Region (northeast, northwest, southeast, southwest)
- Charges (insurance cost — target variable)

# Models Used
- Linear Regression → baseline model.
- Random Forest Regressor → handles non-linear relationships.
- XGBoost Regressor → optimized boosting algorithm for best accuracy.

# Results
- Achieved R² score ~0.80–0.85 depending on model.
- Random Forest and XGBoost performed better than simple linear regression.
- Smoking status and BMI were the most influential features.

# Tech Stack
- Python (NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook for analysis
- Streamlit for deployment
- Machine Learning Models (Regression, Ensemble methods)                                 
