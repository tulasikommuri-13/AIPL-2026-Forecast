# AIPL 2026 - IPL Match Forecast Competition

This project was built for the AIPL 2026 IPL Match Forecast Competition hosted on Kaggle.

## Project Objective

Predict IPL match outcomes using historical IPL ball-by-ball data and machine learning models.

The project includes:
- Data preprocessing
- Match-level feature engineering
- Label creation
- Model training
- Probability prediction
- Kaggle submission pipeline

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## Machine Learning Models Used

- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

---

## Project Workflow

### 1. Data Preparation
- Loaded IPL historical ball-by-ball dataset
- Handled missing values
- Created match-level summaries
- Calculated innings runs and wickets
- Generated competition labels:
  - A_small
  - A_big
  - B_small
  - B_big

### 2. Model Training
- Encoded categorical features
- Split data into training and testing sets
- Trained multiple machine learning models
- Evaluated model accuracy
- Saved trained models using Joblib

### 3. Prediction Pipeline
- Loaded competition test datasets
- Preprocessed future matches
- Generated probability predictions using XGBoost
- Created final Kaggle submission file

---

## Competition Submission

Final submission file:
- `final_submission.csv`

Evaluation metric:
- Log Loss

---

## Repository Files

- `aipl_model.ipynb`
- `modeltrainining.ipynb`
- `prediction.ipynb`
- `final_submission.csv`

---

## Author

Kommuri Tulasi Naga Tejaswini
