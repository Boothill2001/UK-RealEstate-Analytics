# 🏡 UK Real Estate Analytics + Economic Modeling

Welcome to the most comprehensive **Real Estate + Macro-Economic Insight App** ever built for the UK 🇬🇧! This project combines rich transactional property data with macroeconomic indicators to provide powerful predictive insights for investors, policymakers, and data scientists.

---

## 📑 Project Overview

This project aims to:
- Analyze real estate transaction data from the UK (1995–2023)
- Integrate macroeconomic indicators like CPI, GDP, FX rates
- Predict Log_Price using powerful machine learning models
- Deploy an interactive analytics app via Streamlit

---

## 🚀 Key Features

### 📊 Interactive Dashboard
- Built with **Streamlit**
- Filter by year, macro variable, simulate economic scenarios
- Correlation heatmaps, distribution plots, model comparison

### 🔢 Prediction + Modeling
- Predict Log_Price using:
  - ✅ CatBoost
  - ✅ XGBoost
  - ✅ LightGBM
- Batch prediction from uploaded CSV
- SHAP explainability for interpretation
- Model comparison (MAE, RMSE)

### ☁️ Cloud & Scale
- Load/Save datasets and models from **Google Cloud Storage (GCS)**
- Handles large datasets (>28M rows) using efficient memory techniques

---

## 📂 Project Structure

```bash
UK-RealEstate-Analytics/
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 01b_data_preparation.ipynb
├── app/
│   └── streamlit_macro_dashboard_v2.py  # Streamlit app
├── data/
│   └── merged_real_estate_macro.parquet
├── models/
│   ├── CatBoost_model.cbm
│   ├── XGBoost_model.json
│   ├── LightGBM_model.pkl
│   └── feature_names.json
├── .streamlit/config.toml               # UI tweaks
├── Dockerfile (optional deploy)
├── README.md
└── requirements.txt
```

---

## ⚙️ Requirements

- Python 3.8+
- Google Cloud SDK (for GCS operations)

### Python Libraries
```bash
pandas
streamlit
matplotlib
seaborn
scikit-learn
catboost
xgboost
lightgbm
google-cloud-storage
shap
```

---

## 💻 Usage

```bash
# 1. Clone the repo
https://github.com/Boothill2001/UK-RealEstate-Analytics.git

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run Streamlit app
cd app
streamlit run streamlit_macro_dashboard_v2.py
```

---

## 📸 App Preview
![Preview](screenshots/streamlit_preview.png)

---

## 🧠 AI & Economics Combo
This project is tailored for:
- Aspiring **Data Scientists** (especially Economic/Policy-oriented)
- Researchers & Academics studying housing markets
- ML Engineers looking to build end-to-end GCP-integrated pipelines

---

## 📝 Contributions
Open issues or submit pull requests – happy to collaborate!

---

## 📫 Contact
📧 boothill2001.grant@gmail.com  
🌐 [LinkedIn](https://www.linkedin.com/in/nguyenminhtri-datascience/)  
🐙 GitHub: [Boothill2001](https://github.com/Boothill2001)

---

## 📌 Upcoming Improvements
- ✅ Integrate SHAP + batch prediction ✔️
- 📊 Add advanced time-series forecast (Prophet, ARIMA, LSTM)
- 🌍 Extend macro sources beyond UK (e.g., EU-wide data)
- 🚀 Deploy using Streamlit Cloud or GCP Cloud Run

---

> Made with 💡 by Boothill2001
