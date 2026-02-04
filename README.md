# Task: House Price Prediction using Linear Regression

This repository contains **Task-01** for the PRODIGY Machine Learning track.  
The goal of this task is to **predict house prices** based on the following features:

- **Square Footage** (`GrLivArea`)
- **Number of Bedrooms** (`BedroomAbvGr`)
- **Number of Bathrooms** (`FullBath`)

---

## Dataset
- **Source:** Kaggle - [House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)  
- **Files used:** `train.csv` (for training and evaluation)

---

## Features
| Feature Name    | Description                        |
|-----------------|-----------------------------------|
| GrLivArea       | Above grade (ground) living area  |
| BedroomAbvGr    | Number of bedrooms above ground   |
| FullBath        | Number of full bathrooms          |
| SalePrice       | Target variable (house price)     |

---

## Model
- **Algorithm:** Linear Regression  
- **Train/Test Split:** 80% train, 20% test  
- **Evaluation Metrics:** MAE, MSE, R² Score

---

## Steps Taken
1. **Imported libraries**: pandas, numpy, sklearn  
2. **Loaded dataset** and selected required features  
3. **Handled missing values** (dropped)  
4. **Split dataset** into train and test sets  
5. **Trained Linear Regression model** on training data  
6. **Predicted house prices** on test data  
7. **Evaluated model performance** using MAE, MSE, and R²  

---

## Notes
- This notebook is part of the **PRODIGY ML Track**  
- All files for this task are included: `house_price_prediction.ipynb` and `train.csv`
