# Machine Learning - 5 Simple Linear Regression Models

## 📌 Project Overview
This project contains 5 Simple Linear Regression models built using a shared dataset.  
Each model is implemented in a separate Jupyter Notebook and focuses on predicting the target variable using different features.

---

## 📂 Project Structure
data/
data_for_ml.csv
data_for_ml_After_Performing_EDA.csv

notebooks/
Model_1_train_on_hours_studied.ipynb
Model_2_train_on_Sleep_Hours.ipynb
Model_3_train_on_Internet_Usage.ipynb
Model_4_train_on_Study_Method.ipynb
Model_5_train_on_Attendance.ipynb


---

## 📚 Libraries Used
- pandas  
- matplotlib.pyplot  
- scikit-learn  

### From scikit-learn:
- train_test_split (model_selection)  
- StandardScaler (preprocessing)  
- OneHotEncoder (preprocessing)  
- LinearRegression (linear_model)  
- mean_absolute_error (metrics)  
- mean_squared_error (metrics)  
- r2_score (metrics)  

---

## ⚙️ Workflow
- Data loading using pandas  
- Handling missing values  
- Encoding categorical variables  
- Feature scaling using StandardScaler  
- Splitting dataset using train_test_split  
- Training 5 Simple Linear Regression models  
- Model evaluation using MAE, MSE, and R² Score  
- Visualization using matplotlib  

---

## 🤖 Models
Each notebook represents a separate regression model trained on different features of the dataset.

---

## 📊 Evaluation Metrics
- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- R² Score  

---

## ▶️ How to Run
1. Open any notebook inside the `notebooks` folder  
2. Run all cells sequentially  
3. Ensure dataset path is:
