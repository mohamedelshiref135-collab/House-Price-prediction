
🏠 House Price Prediction — Summary

This project uses machine learning to predict house prices based on property features such as:

Location
Carpet/total area
Number of bathrooms
Number of balconies
Floor
Furnishing status
Transaction type
Facing
Overlooking
🔧 Process
Data Cleaning – Handles missing values and removes unnecessary columns.
Feature Engineering – Converts prices from Lac/Cr to rupees, converts area to sqft, and extracts floor/bathroom information.
EDA – Uses visualizations such as scatter plots and box plots to understand price relationships.
Preprocessing – Applies scaling, one-hot encoding, and ordinal encoding.
Modeling – Uses a Random Forest Regressor with 200 trees.
Evaluation – Uses MAE, RMSE, and R² to measure performance.
Model Saving – Saves the trained pipeline as house_price.pkl.
🛠️ Technologies

Python · Pandas · NumPy · Matplotlib · Seaborn · Scikit-learn · Joblib · Jupyter Notebook

🎯 Goal

The goal is to build a complete machine-learning pipeline that takes real-estate data and predicts the expected price of a property.
