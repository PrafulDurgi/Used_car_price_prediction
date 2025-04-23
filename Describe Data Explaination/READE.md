# 🚗 Used Car Price Prediction

![Used Car Banner](https://images.unsplash.com/photo-1570129477492-45c003edd2be)

---

### 📌 **Project Objective**

The aim of this project is to **predict the selling price of used cars** using machine learning techniques. This includes analyzing the data through Exploratory Data Analysis (EDA), performing feature engineering, and building regression models to provide accurate price predictions.

---

### 🏁 Why Used Car Price Prediction?

Used car valuation is a major challenge in the automobile industry. Knowing the fair price of a used vehicle helps:
- 🧾 Buyers make informed decisions.
- 🧑‍💼 Sellers avoid underpricing or overpricing.
- 🏬 Dealers and platforms optimize inventory pricing.

---

### 📂 **Dataset Description**

The dataset `used_car_data.csv` contains the following features:

| Column          | Description                                |
|------------------|--------------------------------------------|
| `name`           | Name of the car (brand + model)            |
| `year`           | Manufacturing year                         |
| `selling_price`  | The price the car is being sold for        |
| `present_price`  | Price when the car was new                 |
| `km_driven`      | Total kilometers driven                    |
| `fuel`           | Fuel type (Petrol, Diesel, CNG, etc.)      |
| `seller_type`    | Seller type (Dealer or Individual)         |
| `transmission`   | Transmission type (Manual or Automatic)    |
| `owner`          | Ownership status (First, Second, etc.)     |

---

### 📊 **Project Workflow**

#### 1. **Exploratory Data Analysis (EDA)**  
- Visualizing selling price distribution  
- Categorical count plots: Fuel, Transmission, Seller Type  
- Correlation heatmap to identify relationships between features  

#### 2. **Feature Engineering**  
- Dropping irrelevant features like `name`  
- One-hot encoding for categorical variables  
- Data cleanup and preparation  

#### 3. **Model Building**  
Models used:
- ✅ Linear Regression  
- ✅ Random Forest Regressor  

**Evaluation Metrics**:
- R² Score  
- RMSE (Root Mean Squared Error)

**Results**:
- 🎯 Random Forest performed better than Linear Regression with higher accuracy and lower error.

---

### 📈 **Visualizations Included**

- Price Distribution Histogram  
- Count Plots (Fuel, Seller Type, Transmission)  
- Correlation Heatmap  
- Actual vs Predicted Price Scatter Plot  

---

### ✅ **Conclusion**

- Cars with higher `present_price` and newer manufacturing years tend to have a higher resale value.  
- Manual transmission cars are more common in the dataset.  
- Random Forest provided better predictive results compared to Linear Regression.

---

### 📸 Car Samples (for aesthetics)

<img src="https://images.unsplash.com/photo-1605559424843-9e4c3e70df1c" width="300"/> <img src="https://images.unsplash.com/photo-1503376780353-7e6692767b70" width="300"/> <img src="https://images.unsplash.com/photo-1612392061783-d6cfc97f43ae" width="300"/>

---

### 🛠️ **Technologies Used**
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

### 🚀 How to Run This Project

1. Clone or download the repository.  
2. Make sure `used_car_data.csv` is in the same directory as the `.ipynb` file.  
3. Open the notebook using **Jupyter Notebook** or **VS Code**.  
4. Run each cell step-by-step to explore the project.


