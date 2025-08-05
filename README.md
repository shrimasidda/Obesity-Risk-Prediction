# Obesity-Risk-Prediction
The system uses XGBoost and health factors like age, weight, diet, and lifestyle to predict obesity risk more accurately than BMI-based models. It categorizes users into detailed weight groups and offers real-time risk forecasts via a web app, enabling personalized insights and informed health choices.

Overview  
Obesity is a growing global health concern linked to serious disorders such as diabetes, cardiovascular diseases, and hypertension. This project predicts obesity risk using **Machine Learning (XGBoost Classifier)** by analyzing age, gender, height, weight, family history, eating habits, and lifestyle factors.  

The system provides accurate risk classifications and a simple **web interface (Streamlit)** for users to input their health details and receive instant predictions.

Objectives  
- Predict obesity risk using health and lifestyle factors.  
- Preprocess and normalize data for model accuracy.  
- Deploy an interactive web interface for real-time predictions.  

Tech Stack  
- **Programming Language:** Python 3.8+  
- **Libraries:** Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, XGBoost, CatBoost, Joblib  
- **Web Framework:** Streamlit  
- **Development Platform:** Google Colab  

Dataset  
- Source: [Kaggle Obesity Dataset](https://www.kaggle.com)  
- Records: 20,757 entries  
- Features: Age, Gender, BMI, family history, physical activity, eating habits, etc.  
- Target: Obesity Level (Insufficient Weight, Normal, Overweight I & II, Obesity I, II & III)  

Features  
✔ Predicts obesity level using XGBoost  
✔ Preprocessing (Normalization, Encoding, Feature Selection)  
✔ User-friendly **Streamlit interface** for real-time predictions  

