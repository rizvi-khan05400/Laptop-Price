# 💻 Laptop Price Prediction – Machine Learning Project

## 📌 Overview
This project builds a machine learning model that predicts laptop prices based on hardware specifications and brand information. It includes complete steps such as data cleaning, preprocessing, model training, evaluation, and conclusion.

---

## 🧼 Data Preprocessing
- Removed missing and inconsistent values  
- Cleaned text fields (RAM, Storage, CPU, GPU, etc.)  
- Extracted numerical values from mixed strings  
- Encoded categorical variables (Brand, CPU, GPU, Storage Type)  
- Standardized numerical features where necessary  

---

## 🧠 Models Used
- **Linear Regression** (baseline)  
- **Random Forest Regressor**  
- **CatBoost Regressor** (best-performing model)


**Note: I apply CatBoost Regressor model**

---

## 📊 Model Evaluation Metrics
- **MAE** – Mean Absolute Error  
- **MSE** – Mean Squared Error  
- **RMSE** – Root Mean Squared Error  
- **R² Score** – Goodness of fit  

CatBoost produced the highest accuracy and required the least preprocessing.

---

## 🔍 Key Insights
- Price is mainly affected by:  
  - CPU generation  
  - RAM size  
  - GPU type  
  - Storage type (SSD/HDD)  
  - Display resolution  
- CatBoost handles categorical features efficiently and performs best.

---

## 🚀 Results
- The final model predicts laptop prices with high accuracy.  
- The system can be used for:  
  - E-commerce pricing  
  - Market comparison  
  - Laptop recommendation system  
  - Inventory valuation  

---

## 🛠 Technologies Used
- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- CatBoost  
- Jupyter Lab  

---

## 🔮 Future Improvements
- Add more laptop models for better generalization  
- Hyperparameter tuning for higher accuracy  
- Deploy using Flask/FastAPI  
- Build a web UI for predictions  
- Try deep learning or stacking models  

---

## 📌 Conclusion
This project demonstrates a complete machine learning workflow — from data preprocessing to model evaluation. The final CatBoost model provides reliable predictions and can be implemented in real-world applications involving price prediction or product recommendation.

---

**Deployment Link: https://huggingface.co/spaces/rizvikhan05400/Laptop-Price-Prediction**
