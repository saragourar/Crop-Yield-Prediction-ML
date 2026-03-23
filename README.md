# 🌾 Crop Yield Prediction Using Machine Learning

##  Overview
This project aims to predict crop yield using advanced machine learning techniques based on environmental and agricultural data.

---

## 📊 Dataset
The dataset was obtained from Kaggle:

👉 https://www.kaggle.com/YOUR-DATASET-LINK

### Features:
- Area (region)
- Item (crop type)
- Year
- average_rain_fall_mm_per_year
- pesticides_tonnes
- avg_temp
- hg/ha_yield (target)

---

##  Methodology

### Data Preprocessing:
- Removing duplicates and unnecessary columns  
- Handling missing values  
- Encoding categorical variables (OneHotEncoder)  
- Feature scaling (StandardScaler)  

### Data Augmentation:
- Synthetic dataset generation using bootstrapping  
- Adding small noise to numeric features  

---

##  Models Used
- Artificial Neural Network (ANN) with PCA  
- Random Forest (with GridSearchCV)  
- XGBoost Regressor  

---

## 📈 Evaluation Metrics
- R² Score  
- MAE (Mean Absolute Error)  
- RMSE (Root Mean Squared Error)  

---

## Results
- ANN, Random Forest, and XGBoost were compared  
- Performance evaluated using R², MAE, and RMSE  
- ANN showed strong performance with dimensionality reduction (PCA)  

---

## Outputs
- Performance comparison plots (R², MAE, RMSE)  
- Actual vs Predicted plots for each model  


