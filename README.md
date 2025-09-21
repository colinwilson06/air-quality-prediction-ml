# Air Quality Prediction (Machine Learning Project)

Proyek ini dibuat untuk memprediksi **kualitas udara (Air Quality Index)** berdasarkan parameter lingkungan dan polutan.  
Model machine learning yang digunakan adalah **Random Forest, XGBoost, dan Voting Classifier (ensemble)**.  
Akurasi terbaik yang dicapai adalah **97%** dengan Voting Classifier berbobot (2:1).  

## Dataset
Dataset: *Air Quality and Pollution Assessment* (Kaggle)  

**Fitur yang digunakan:**
- Temperature (°C)  
- Humidity (%)  
- PM2.5 (μg/m³)  
- PM10 (μg/m³)  
- NO₂ (ppb)  
- SO₂ (ppb)  
- CO (ppm)  
- Proximity to Industrial Areas (km)  
- Population Density (people/km²)

**Target (Air Quality Levels):**
- Good  
- Moderate  
- Poor  
- Hazardous

## Teknologi
- Python  
- Pandas, Numpy  
- Scikit-learn  
- XGBoost  
- Matplotlib, Seaborn  
- Streamlit  
- Joblib


## Cara Menjalankan
1. Clone repo ini:
   ```bash
   git clone https://github.com/username/air-quality-prediction-ml.git
   cd air-quality-prediction-ml

2. Install dependencies:
   pip install -r requirements.txt

3. Jalankan aplikasi Streamlit:
   streamlit run src/app.py

   **Dapat diakses secara langsung menggunakan link berikut ini**
   (https://dckaolml.streamlit.app/)


## Hasil Model

- Random Forest: Akurasi 96%
- XGBoost: Akurasi 96%
- Voting Classifier (Weighted 2:1): Akurasi 97%

## Video Demo
https://youtu.be/SvFmxusv1PM

## Documentation
- [Project Report (PDF)](docs/laporan_aol_ml_1.pdf)
- [Screenshots](docs/Screenshots/)

## Tim 
- Colin Wilson – Model, Laporan
- David Arifin – Model, Laporan
- Kenneth Angelo Sulaiman – Integrasi model & Streamlit, Deployment, Laporan
