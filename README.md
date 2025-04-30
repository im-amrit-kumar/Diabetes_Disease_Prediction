🧠 Diabetes Disease Prediction

This project uses machine learning techniques to predict diabetes based on health indicators. The dataset is sourced from the 2015 Behavioral Risk Factor Surveillance System (BRFSS) and includes features related to physical and mental health, BMI, smoking habits, and more.

📂 Dataset

Source: diabetes_012_health_indicators_BRFSS2015.csv

Target Variable: Diabetes_012 (0 = No Diabetes, 1 = Pre-diabetes, 2 = Diabetes)

📊 Key Steps

Data Loading & Cleaning:

Pandas and NumPy for manipulation

Null checks and info summary

Exploratory Data Analysis (EDA):

Count plots and correlations

Target class distribution visualization

Preprocessing:

Feature scaling

Handling imbalanced classes using SMOTE

Modeling:

Random Forest Classifier

XGBoost Classifier with hyperparameter tuning (RandomizedSearchCV)

Evaluation:

Accuracy, Confusion Matrix, ROC AUC Score

SHAP for model interpretability

📈 Libraries Used

pandas, numpy

matplotlib, seaborn

sklearn, xgboost, shap

imblearn (SMOTE for class balancing)

🧪 Results

The model achieved promising accuracy and interpretability using ensemble methods. SHAP visualizations highlight the impact of features on predictions.

💡 Future Improvements

Use more advanced ensembling (e.g., stacking)

Deploy as a web app with interactive input

Add support for multiclass classification (Pre-diabetes included)

🚀 How to Run

pip install -r requirements.txt

jupyter notebook "Diabetes Disease Prediction.ipynb"
