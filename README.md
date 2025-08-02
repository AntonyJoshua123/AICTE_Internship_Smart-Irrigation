# AICTE_Internship_Smart-Irrigation
# Smart Irrigation System 🌾💧
This project is part of the AICTE Internship program and aims to build a **Smart Irrigation System** that predicts whether sprinklers should be ON or OFF based on real-time soil and environmental sensor readings.

## 🚀 Project Overview
Traditional irrigation systems lack automation and waste large amounts of water due to improper scheduling. This smart system uses **machine learning** to analyze moisture data from **19 sensors** and controls **3 pumps/sprinklers** efficiently.

## 🧠 Technologies & Tools Used
- **Python 3.13.3**
- **Jupyter Notebook** (for model development)
- **Visual Studio Code** (code editor)
- **Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn** (data preprocessing and model training)
- **XGBoost** (for advanced classification)
- **Streamlit** (to build a user-friendly web app)
- **Joblib** (to serialize the model)

## 📁 Project Structure
- `AICTE_Internship_Smart_Irrigation.ipynb` – Main notebook for training and evaluating ML models  
- `irrigation_machine.csv` – Dataset used containing sensor readings and pump status  
- `Farm_Irrigation_System.pkl` – Trained ML model exported using Joblib  
- `app.py` – Streamlit web app for predicting sprinkler status  

## 🧪 Methodology
1. **Data Collection & Exploration**  
   Dataset includes soil moisture, temperature, humidity, soil type, and crop type.
   
2. **Preprocessing**  
   Feature selection, encoding categorical variables, and normalization.

3. **Model Training**  
   Classification models (Random Forest, SVM, XGBoost) were trained and evaluated.

4. **Deployment**  
   Best model deployed using a **Streamlit** app where users can input sensor values and get irrigation recommendations instantly.

## 🌿 App Features
- Accepts **scaled input values** from 19 sensors (0.0 to 1.0)  
- Predicts ON/OFF status for 3 pumps/sprinklers controlling different land parcels  
- Clean, interactive UI for real-time prediction and visualization  

## 🔗 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/AntonyJoshua123/AICTE_Internship_Smart-Irrigation.git
   cd AICTE_Internship_Smart-Irrigation
