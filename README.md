# Road Accidents in India - Predictive Modeling

Machine Learning project to predict road accident numbers and classify high-risk years in India (2016–2022).

## Project Structure
- `notebooks/` → All Jupyter notebooks
  - 01_Preprocessing_and_EDA.ipynb
  - 02_Regression_Model.ipynb
  - 03_Classification_Model.ipynb
- `NewDatasets/` → Cleaned dataset


## Objective
- Regression: Predict exact number of accidents
- Classification: Predict high-risk (>5,000 accidents) vs low-risk years
- Focus: Kerala insights and road safety recommendations

## Key Results
- **Regression**: Linear Regression (R² ≈ 0.993, MAE ≈ 939)
- **Classification**: Logistic Regression (Accuracy 100%, ROC-AUC 1.0)
- Main Insight: Previous year's accidents strongly predict current year (98% importance)

## How to Run
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Open notebooks in Jupyter Notebook / VS Code

## Author
Mina