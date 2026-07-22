# 🏠 House Price Prediction using Linear Regression

## 📌 Project Overview

This project focuses on predicting house prices using Machine Learning. The objective is to build a regression model capable of estimating the selling price of a house based on its features.

The project follows a complete end-to-end Machine Learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model building, evaluation, and hyperparameter tuning.

This project was completed as part of my Machine Learning learning journey.

---

# 🎯 Business Problem

Accurately estimating house prices is important for:

- Real estate companies
- Property buyers
- Property sellers
- Investors

A reliable prediction model can help estimate the market value of a property based on historical housing data.

---

# 📂 Dataset Information

- Dataset: House Prices Dataset
- Target Variable:
  - `SalePrice`
- Problem Type:
  - Regression

The dataset contains information about different house characteristics such as:

- Overall Quality
- Living Area
- Garage Size
- Basement Area
- Number of Bathrooms
- Year Built
- Neighborhood
- Lot Area
- And many more housing features.

---

# 🛠️ Machine Learning Workflow

```
Business Understanding
        ↓
Dataset Understanding
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis (EDA)
        ↓
Feature Engineering
        ↓
Feature Scaling
        ↓
Train-Test Split
        ↓
Model Building
        ↓
Model Evaluation
        ↓
Hyperparameter Tuning
        ↓
Final Model
```

---

# 📊 Exploratory Data Analysis (EDA)

Performed:

- Missing Value Analysis
- Duplicate Check
- Correlation Heatmap
- Distribution Analysis
- Feature Relationship Analysis
- Outlier Detection

---

# ⚙️ Feature Engineering

Performed several feature engineering steps, including:

- Label Encoding
- One-Hot Encoding
- Log Transformation
- Feature Scaling using StandardScaler
- Creation of new engineered features

Examples:

- TotalHouseSF
- TotalBathrooms
- HouseAge
- RemodelAge
- TotalPorchSF

---

# 🤖 Models Used

The following regression models were trained and compared:

- Linear Regression
- Ridge Regression
- Lasso Regression

Hyperparameter tuning was performed to improve model performance.

---

# 📈 Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

# 🏆 Final Results

Best Performing Model:

**Ridge Regression (with Log Transformation)**

Evaluation Results:

- R² Score: **0.8975**
- Strong generalization performance on unseen data.

---

# 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

# 📁 Project Structure

```
House-Price-Prediction/
│
├── README.md
├── requirements.txt
├── House_Price_Prediction.ipynb
├── house_price.csv
├── images/
│   ├── scatter_plot.png
│   ├── correlation_heatmap.png
│   ├── actual_vs_predicted.png
│   └── residual_plot.png
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/House-Price-Prediction.git
```

Move into the project folder

```bash
cd House-Price-Prediction
```

Install the required libraries

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook.

---

# 📚 What I Learned

Through this project I learned:

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Linear Regression
- Ridge Regression
- Lasso Regression
- Model Evaluation
- Hyperparameter Tuning
- Building a complete Machine Learning pipeline

---

# 🔮 Future Improvements

Possible future improvements include:

- Random Forest Regressor
- XGBoost Regressor
- LightGBM
- Feature Selection
- Model Deployment using Streamlit or Flask

---

# 👨‍💻 Author

**Mohammed Dhinojwala**

Aspiring AI / Machine Learning Engineer

Currently documenting my journey by building Machine Learning projects from scratch and sharing my progress publicly.

If you found this project helpful, feel free to ⭐ the repository.
