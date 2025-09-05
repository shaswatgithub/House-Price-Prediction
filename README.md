# 🏡 House Price Prediction using Machine Learning

## 📌 Project Topic
**House Price Prediction using Supervised Machine Learning in Python**  
A project that predicts house prices using features like location, lot area, type of dwelling, and more, using regression models.

---

## 📖 What This Project is About

This project aims to **predict the sale price of a house** using machine learning algorithms based on various housing features. By analyzing a dataset of real estate records, we explore, clean, and transform the data and use regression techniques to model and predict housing prices.

---

## 🛠 Languages and Libraries Used

### 🧠 **Languages**
- Python 🐍

### 📚 **Libraries**
- `pandas` 🗃️ – Data manipulation and analysis
- `matplotlib` 📊 – Data visualization
- `seaborn` 🌊 – Advanced data visualization
- `sklearn` 🤖 – Machine Learning models & preprocessing

---

## 🔍 What You’ll Learn / Get from This Project

- How to **import and preprocess** real estate data
- Performing **Exploratory Data Analysis (EDA)** with heatmaps and bar plots
- Handling **missing values** and **irrelevant features**
- Using **One-Hot Encoding** to convert categorical data
- Splitting data into **train/test sets**
- Training and comparing three regression models:
  - Support Vector Regressor (SVR)
  - Random Forest Regressor
  - Linear Regression
- Evaluating models using **Mean Absolute Percentage Error (MAPE)**

---

## 🧮 Final Results (Model Performance)

| Regression Model           | MAPE (Error) 📉 |
|---------------------------|----------------|
| ✅ Support Vector Machine  | **0.1870**      |
| 🌲 Random Forest Regressor | 0.1929         |
| 📈 Linear Regression       | 0.1874         |

🎯 **Best Performing Model:** **SVM Regressor**  
(Least error among all tested models)

---

## 🗂️ Project Structure

1. **📦 Step 1**: Import Libraries & Load Dataset
2. **🧹 Step 2**: Data Preprocessing & Type Identification
3. **📊 Step 3**: Exploratory Data Analysis (EDA)
4. **🧼 Step 4**: Data Cleaning – Remove Nulls, Drop Irrelevant Columns
5. **🧠 Step 5**: Encode Categorical Features with OneHotEncoder
6. **🔀 Step 6**: Split Dataset into Training & Testing
7. **📈 Step 7**: Train & Evaluate ML Models (SVM, RF, Linear)
8. **🏆 Final Step**: Compare Accuracy and Choose Best Model

---

## 📎 Dataset Details

- Total Records: `2919`
- Total Features: `13`
- Target: `SalePrice`

📥 **Note**: Dataset used: `HousePricePrediction.xlsx`  
(*Ensure it is in your working directory*)

---

## 💬 Conclusion

This project helps us gain insights into the housing market by identifying which features most impact price. By the end, we can predict house prices using trained models with decent accuracy and evaluate models to pick the best one.

> 🚀 Future Work: Try Boosting (XGBoost, LightGBM) or feature selection techniques to improve performance!

---

## 🤝 Contributing

Feel free to fork this project, raise issues, or contribute! 🙌

---

## 📄 License

This project is open-source and available under the MIT License.

