# 🏠 House Price Prediction App with Gradio

This project predicts house prices using a **Random Forest Regressor** trained on the USA Housing Dataset.

## 🚀 Project Journey
1. **Data Cleaning**: Handled missing values and removed illogical zero-price entries.
2. **Outlier Removal**: Used the IQR method to remove extreme price outliers, improving model stability.
3. **Feature Engineering**: Applied Label Encoding and StandardScaler to ensure all features are numerical and on the same scale.
4. **Model Performance**: Improved $R^2$ Score from a negative value to **0.51** after cleaning.

## 💻 UI Demo
The app features a user-friendly interface built with **Gradio**, allowing users to input house details and get instant price estimates.

## 🛠️ How to Run
1. Install requirements: `pip install -r requirements.txt`
2. Run the app: `python app.py`
