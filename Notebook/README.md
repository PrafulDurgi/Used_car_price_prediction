# 🚗 Used Car Price Prediction

## 📌 Project Overview

This project focuses on building a machine learning model to predict the **selling price of used cars** using historical data. It includes complete steps from data preprocessing to model evaluation, with visualizations and metrics.

**#🧠 Objective**

To build a machine learning model that accurately predicts the selling price of used cars based on various features like the car's age, mileage, fuel type, transmission, and ownership details. The goal is to assist individuals or businesses in understanding vehicle pricing trends and making data-driven pricing decisions.

Methodology This project follows a complete data science workflow, including:

**1  Data Collection**

Real-world dataset containing used car listings with pricing details.

Dataset includes features such as car name, year, kilometers driven, fuel type, seller type, etc.

**2  Data Preprocessing**

Cleaning and encoding categorical variables.

Removing irrelevant or redundant columns.

Handling missing values (if any).

**3  Exploratory Data Analysis (EDA)**

Understanding feature distributions (e.g., selling price, fuel types).

Visualizing correlations between variables.

Outlier detection and feature importance.

**4  Model Building**

Features and target variable selection.

Splitting data into training and testing sets.

Training a Random Forest Regressor for price prediction.

**5  Model Evaluation**

Evaluating model performance using:

📉 R² Score (Goodness of Fit)

📉 Mean Squared Error (MSE)

Visualizing actual vs. predicted prices.

---

## 📁 Files in this Repository

- `Used_Car_Price_Prediction_GitHub.ipynb` - Jupyter Notebook with full analysis, modeling, and plots
- `used_car_data.csv` - Dataset used in the project (if uploaded)
- `README.md` - Project overview and instructions

---

## 📊 Features Used

- Year of Manufacture  
- Kilometers Driven  
- Fuel Type  
- Seller Type  
- Transmission  
- Owner History  
- Present Price & Selling Price

---

## 🧪 Techniques & Tools

- **Python, Pandas, NumPy**
- **Data Visualization**: Matplotlib, Seaborn
- **Model**: Random Forest Regressor
- **Evaluation Metrics**: R² Score, Mean Squared Error (MSE)

---

## 📈 Results

The model performs well in predicting car prices. A scatter plot of **Actual vs Predicted values** is included for validation.

**## ✅ Conclusion**

- We performed EDA and uncovered key insights.
- Feature engineering used one-hot encoding for categorical features.
- Built two regression models: Linear Regression and Random Forest.
- Random Forest achieved higher R² and lower RMSE than Linear Regression.

---

## ✅ How to Use

1. Clone the repository or download the notebook
2. Make sure the dataset CSV file is in the same directory
3. Run the notebook in JupyterLab, VSCode, or Google Colab

---

## 🙌 Acknowledgment

Inspired by real-world datasets from the automobile sector. Great for learning EDA and regression modeling.
