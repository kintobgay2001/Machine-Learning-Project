# Product Demand Forecasting using Regression Models

This project focuses on predicting product demand (Units Sold) based on pricing features using various regression algorithms.

## 📊 Dataset
- Sourced from: [Kaggle/Amankharwal GitHub Dataset](https://raw.githubusercontent.com/amankharwal/Website-data/master/demand.csv)
- Features used: Total Price, Base Price
- Target: Units Sold

## 📈 Exploratory Data Analysis
- Checked for null values and cleaned data
- Visualized correlations using scatter plots and heatmaps (Plotly, Seaborn, Matplotlib)

## 🤖 Models Implemented
1. **Decision Tree Regressor**
2. **Random Forest Regressor**
3. **K-Nearest Neighbors Regressor**
4. **Support Vector Regressor (SVR)**

## 🧠 Workflow
- Feature engineering and train-test split using scikit-learn
- Model training and prediction on new price inputs
- Accuracy evaluated using R² score

## 🔍 Prediction Example
```python
Input: [[133.00, 140.00]]
Output: Predicted Units Sold = ~59.17
