# 🏠 House Price Prediction

## Problem Statement
Predict the sale price of residential homes based on features like area, quality, rooms, garage, basement, and location.

## Dataset
- **Source:** Kaggle - House Prices: Advanced Regression Techniques
- **Rows:** 1,460 houses
- **Features:** 79 features + 1 target (SalePrice)

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn (Linear Regression, Random Forest)
- Matplotlib, Seaborn

## Approach

### 1. Data Preprocessing
- Filled missing values (median for numbers, mode for categories)
- Label Encoding for categorical features

### 2. Models Used
- Linear Regression (baseline)
- Random Forest Regressor (100 trees)

### 3. Evaluation Metrics
- R² Score (accuracy)
- RMSE (average error in dollars)

## Results

| Model | R² Score | Accuracy | RMSE |
|-------|----------|----------|------|
| Linear Regression | 0.837 | 83.7% | $28,000 |
| Random Forest | 0.894 | 89.4% | $21,000 |

**Winner:** Random Forest

## Key Insights

### Top 5 Important Features
1. **OverallQual** - Overall quality of house
2. **GrLivArea** - Above ground living area
3. **TotalBsmtSF** - Total basement area
4. **GarageCars** - Garage size
5. **YearBuilt** - Year constructed

## How to Run

### Google Colab
1. Open colab.research.google.com
2. Upload the notebook
3. Upload train.csv from Kaggle
4. Run all cells (Runtime → Run all)
