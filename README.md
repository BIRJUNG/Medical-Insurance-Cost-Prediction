# 💰 Medical Insurance Cost Prediction

A production-grade machine learning project that predicts **individual medical insurance charges** using demographic and health-related features, leveraging **statistical modeling, feature engineering, and regression techniques**.

---

## 🚀 Project Overview

Healthcare costs are highly variable and difficult to estimate. This project builds a **complete end-to-end regression pipeline** to predict insurance charges based on user attributes such as age, BMI, smoking status, and region.

The solution combines:

- Exploratory Data Analysis (EDA)
- Feature Engineering
- Regression Modeling
- Model Evaluation & Optimization

---

## 🎯 Business Problem

Insurance providers face challenges in:

- Pricing policies accurately  
- Managing financial risk  
- Identifying high-cost individuals  

### 💡 Solution Impact

- Improves **premium pricing accuracy**  
- Enables **risk-based customer segmentation**  
- Supports **cost forecasting**  
- Helps in **policy optimization**  

### 🏢 Real-world Applications

- Health insurance pricing  
- Risk assessment models  
- Healthcare cost forecasting  
- Actuarial analytics  

---

## 🧠 Solution Approach

### 1. Data Understanding

Dataset includes:

- `age`
- `sex`
- `bmi`
- `children`
- `smoker`
- `region`
- `charges` (target variable)

---

### 2. Exploratory Data Analysis (EDA)

Key insights extracted:

- Strong correlation between **smoking and higher charges**
- BMI and age significantly influence costs
- Non-linear relationships observed in features

Visualization techniques used:

- Histograms  
- Boxplots  
- Correlation heatmaps  

---

### 3. Data Preprocessing

- Handling missing values (if any)
- Encoding categorical variables (One-Hot Encoding)
- Feature scaling (if required)
- Outlier analysis

---

### 4. Feature Engineering

- Interaction features (e.g., smoker × BMI)
- Polynomial features (optional)
- Log transformation for skewed distributions

---

### 5. Model Training

Models evaluated:

- Linear Regression (Baseline)
- Ridge Regression
- Lasso Regression
- Random Forest Regressor
- XGBoost Regressor (best performing)

---

### 6. Model Evaluation

Evaluation metrics used:

- R² Score  
- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)  

---

## 📊 Evaluation Metrics

- **R² Score** → Model explanatory power  
- **MAE** → Average absolute error  
- **RMSE** → Penalizes large errors  

---

## 🏗️ Project Pipeline

Raw Data  
↓  
Data Cleaning  
↓  
EDA  
↓  
Feature Engineering  
↓  
Encoding & Scaling  
↓  
Model Training  
↓  
Model Evaluation  
↓  
Final Model  

---

## 💻 Model Usage

Example:

Input:

- Age: 35  
- BMI: 28  
- Smoker: Yes  
- Children: 2  
- Region: Southeast  

Output:

Predicted Insurance Cost: **$32,500 (approx.)**

---

## 📁 Project Structure

Medical-Insurance-Cost-Prediction/  
│  
├── notebook.ipynb             # Main project notebook  
├── README.md  
├── requirements.txt  
│  
├── artifacts/  
│   ├── model.pkl  
│   └── preprocessing.pkl  

---

## ⚙️ Installation

### 1. Clone Repository

git clone https://github.com/your-username/medical-insurance-prediction.git  
cd medical-insurance-prediction  

---

### 2. Create Virtual Environment

python3 -m venv venv  
source venv/bin/activate  

---

### 3. Install Dependencies

pip install -r requirements.txt  

---

### 4. Run Notebook

jupyter notebook  

---

## 🧪 Example Insight

- Smokers have **significantly higher insurance costs**
- Charges increase with age and BMI
- Non-smokers show more stable cost distribution

---

## 🧠 Key Learnings

- Importance of **EDA in regression problems**
- Feature interactions can significantly improve performance
- Difference between **linear vs ensemble models**
- Handling skewed target variables
- Trade-offs between interpretability and performance

---

## ⚠️ Deployment Note

For production deployment:

- Save model using:
  
  model.save_model("model.json")

- Avoid version conflicts with pickled models

---

## 🔥 Future Improvements

- Use **Deep Learning regression models**
- Add **real-world healthcare datasets**
- Deploy with **Streamlit / FastAPI**
- Integrate **real-time prediction APIs**
- Add **explainability (SHAP values)**

---

## 📌 Tech Stack

- Python  
- Scikit-learn  
- XGBoost  
- Pandas / NumPy  
- Matplotlib / Seaborn  

---

## 👨‍💻 Author

**Birjung Thapa**  
Master’s in Data Science  
University of Colorado Boulder  

---

## ⭐ Support

If you found this project useful:

⭐ Star the repository  
📢 Share it with others  

---
