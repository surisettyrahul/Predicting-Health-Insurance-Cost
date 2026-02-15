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
- **Docker**: Containerized the Streamlit app for consistent deployment 

# Results
- Achieved R² score ~0.80–0.85 depending on model.
- Random Forest and XGBoost performed better than simple linear regression.
- Smoking status and BMI were the most influential features.

# Tech Stack
- Python (NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook for analysis
- Streamlit for deployment
- Machine Learning Models (Regression, Ensemble methods)
- **Docker**: Containerized the Streamlit app for consistent deployment

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/Predicting-Health-Insurance-Cost.git
cd Predicting-Health-Insurance-Cost
```
### 2. Running locally with Python
Make sure you have Python 3.x installed.
#### Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows
```
#### Install dependencies:
```bash
pip install -r requirements.txt
```
#### Run the Streamlit app:
```bash
streamlit run app.py
```
## 3. Running with Docker
To run the app in a Docker container:

**Build the Docker image:**  
```bash
docker build -t health-insurance-app .
```
**Run the Docker container:**
```bash
docker run -p 8501:8501 health-insurance-app
```

Open your browser at http://localhost:8501
 to view the app.                             
