# 🌬️ Air Quality Prediction (Machine Learning Project)

This project aims to predict the **Air Quality Index (AQI)** based on environmental parameters and pollutant levels.  
The machine learning models used include **Random Forest, XGBoost, and a Weighted Voting Classifier**.  
The best accuracy achieved is **97%** using the weighted Voting Classifier (2:1).

## 🗂️ Dataset
**Source:** *Air Quality and Pollution Assessment* (Kaggle)  

**Features used:**
- 🌡️ Temperature (°C)  
- 💧 Humidity (%)  
- 🏭 PM2.5 (μg/m³)  
- 🏭 PM10 (μg/m³)  
- 🌫️ NO₂ (ppb)  
- 🌫️ SO₂ (ppb)  
- 🔥 CO (ppm)  
- 🏭 Proximity to Industrial Areas (km)  
- 👥 Population Density (people/km²)

**Target (Air Quality Levels):**
- ✅ Good  
- ⚠️ Moderate  
- ❌ Poor  
- ☠️ Hazardous

## 🛠️ Technologies
- Python  
- Pandas, Numpy  
- Scikit-learn  
- XGBoost  
- Matplotlib, Seaborn  
- Streamlit  
- Joblib


## 🚀 How to Run

### Step 1: Clone repo
```bash
git clone https://github.com/username/air-quality-prediction-ml.git
cd air-quality-prediction-ml
``` 

### Step 2: Install dependencies
```bash
pip install -r requirements.txt
```

### Step 3: Run the Streamlit application
```bash
streamlit run src/app.py
```

   **💻 Access the app directly via:** [Streamlit App](https://dckaolml.streamlit.app/)


## 📈 Model Results

- Random Forest: Accuracy 96%
- XGBoost: Accuracy 96%
- Voting Classifier (Weighted 2:1): Accuracy 97%

## 🎥 [Video Demo](https://youtu.be/SvFmxusv1PM)


## 📄 Documentation
- 📑 [Project Report (PDF)](docs/laporan_aol_ml.pdf)
- 🖼️ [Screenshots](docs/Screenshots/)

## 👥 Team
- Colin Wilson – Model Development, Report
- David Arifin – Model Development, Report
- Kenneth Angelo Sulaiman – Model Integration & Streamlit, Deployment, Report
