# 🏠 House Price Prediction using Linear Regression

This project is part of the **PRODIGY ML Internship - Task 01**. It involves building a **Linear Regression model** to predict house prices using key features like:

- ✅ Square footage (`GrLivArea`)
- ✅ Number of bedrooms (`BedroomAbvGr`)
- ✅ Number of bathrooms (`FullBath` / `TotRmsAbvGrd`)

---

## 📂 Dataset

We use the [Kaggle - House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data) dataset.

---

## 🛠️ Tools & Technologies

- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-Learn
- Plotly (3D Visualization)
- Matplotlib / Seaborn (EDA)

---

## 🧠 How to Run
1. Clone the repo: https://github.com/Palash1249/PRODIGY_ML_01.git
2. Install requirements: pip install -r requirements.txt
3. Run the notebook: Open house_price_prediction.ipynb in Jupyter Notebook or VSCode.


## Results

We trained a Linear Regression model to predict house prices based on:
- Square footage
- Number of bedrooms
- Number of bathrooms

### 📊 Actual vs Predicted Prices (3D Plot)

The following 3D scatter plot visualizes how well the model predicts house prices based on the given features:

![3D Plot](result/Screenshot%202025-05-16%20103744.png)

- 🟠 Orange dots represent **actual house prices**
- 🔵 Blue dots represent **predicted house prices**
- The plot helps visualize the performance and variance across the feature space

### 🔍 Model Performance

- **R² Score**: `0.89`
- **Mean Absolute Error (MAE)**: `21000`
- **Root Mean Squared Error (RMSE)**: `27000`

These metrics suggest that the model performs reasonably well in estimating house prices.
