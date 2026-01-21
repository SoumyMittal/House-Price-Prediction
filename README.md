# 🏠 House Price Prediction using Machine Learning

This project predicts house prices using **Linear Regression** on numerical housing data.  
It demonstrates a complete **regression workflow** including data inspection, exploratory data analysis, feature scaling, model training, and evaluation.

---

## 📌 Problem Statement
The goal of this project is to build a machine learning model that can predict house prices based on various numerical features such as income, location, and population.

---

## 📂 Dataset
- **California Housing Dataset** (from scikit-learn)
- Contains **20,640 housing records**
- All features are numerical

### Target Variable
- `MedHouseVal` → Median house value

---

## ⚙️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib & Seaborn
- Scikit-learn

---

## 🔍 Project Workflow

1. Data loading and inspection  
2. Exploratory Data Analysis (EDA)  
3. Feature and target separation  
4. Train-test split  
5. Feature scaling using StandardScaler  
6. Model training using Linear Regression  
7. Model evaluation using MSE and RMSE  

---

## 📊 Results
- **RMSE:** ~2.07  
- The model provides a reasonable baseline performance for house price prediction.

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/SoumyMittal/House-Price-Prediction
2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
3. Open the notebook:
   ```bash
   jupyter notebook house_price_prediction.ipynb
4. Run all cells.

📌 Conclusion

This project demonstrates how regression techniques can be applied to real-world numerical data.
Linear Regression provides a strong baseline and helps understand feature influence on house prices.

🚀 Future Improvements

• Try Ridge or Lasso Regression
• Use Random Forest Regressor
• Perform advanced feature engineering
