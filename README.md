# 🏠  House Price Prediction | End-to-End ML Project


An end-to-end **Machine Learning regression project** that predicts **housing prices in Bangalore** using real-world data.  
The project demonstrates the complete ML lifecycle — from **data preprocessing and model training** to **deployment as a production-ready web application**.

---

## 📌 Problem Statement

Real estate pricing depends on multiple factors such as location, property size, and number of rooms.  
Manually estimating property prices can be inconsistent and inaccurate.

This project aims to **build a reliable machine learning model** that predicts house prices based on historical housing data and makes it accessible through a **simple web interface**.

---

## 🎯 Project Objectives

- Perform supervised learning for house price prediction  
- Apply regression techniques on real-world housing data  
- Carry out data cleaning, feature engineering, and EDA  
- Train and evaluate a machine learning model  
- Deploy the trained model using Flask as a web application  

---

## 📊 Dataset Information

- Dataset sourced from **Kaggle**
- Contains Bangalore housing data including:
  - Location
  - Total square feet
  - Number of bedrooms (BHK)
  - Number of bathrooms
  - Price



---

## 🧠 Machine Learning Workflow

### 1️⃣ Data Preprocessing
- Handled missing and inconsistent values  
- Removed outliers for better model performance  
- Converted categorical features using encoding techniques  

### 2️⃣ Exploratory Data Analysis (EDA)
- Distribution analysis of prices and property sizes  
- Location-based price comparison  
- Correlation analysis between features  

### 3️⃣ Model Building
- Implemented regression-based machine learning model  
- Trained the model on cleaned and engineered features  
- Evaluated performance using standard regression metrics  

### 4️⃣ Model Evaluation
- R² Score  
- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)  

---

## 🛠️ Technologies & Tools Used

### Programming & ML
- Python  
- NumPy  
- Pandas  
- Scikit-learn  

### Visualization
- Matplotlib  
- Seaborn  

### Deployment
- Flask  
- HTML, CSS, JavaScript  
- Heroku  

---



## 📁 Project Structure

```bash
Bangalore-Housing-Price-Prediction/
│
├── bangalore_house_price_prediction.ipynb
├── app.py
├── model/
│   └── house_price_model.pkl
├── templates/
│   └── index.html
├── static/
│   └── style.css
├── README.md
└── Screenshots/
    └── BangaloreHousePricePredictionHeroku.JPG
