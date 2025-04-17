# 🏡 UK Real Estate Analytics + Economic Modeling

Welcome to the most advanced **Real Estate + Macro-Economic Insight System** for the UK 🇬🇧! This project goes beyond prediction — it empowers analysts, investors, and policymakers with forecasting, simulation, and explainability tools that combine housing data with economic indicators.

---

## 📑 Project Overview
This project aims to:

- Analyze UK real estate transaction data (1995–2023)
- Integrate macroeconomic indicators (GDP, CPI, interest rate, FX, etc.)
- Predict property prices using state-of-the-art ML models
- Explain predictions with SHAP/LIME
- Simulate economic scenarios: "What if inflation increases by 2%?"
- Deploy a full-stack Streamlit app with cloud-hosted models & monitoring

---

## 🚀 Key Features

### 📊 Interactive Dashboard (Streamlit)
- Filter by year and macroeconomic variable
- Visualize trends, distributions, correlations
- Run predictive simulations with custom macro inputs
- Batch prediction via uploaded CSVs

### 🔢 Machine Learning Models
- Trained & compared:
  - ✅ CatBoost
  - ✅ XGBoost
  - ✅ LightGBM
- SHAP explainability integrated
- MAE/RMSE comparison dashboard

### 🧠 Economic Intelligence
- Elasticity analysis (e.g., how much prices change with GDP variation)
- Scenario simulation (interest rate hike, recession modeling)
- Explainable AI with SHAP summary & waterfall

### ☁️ Cloud-Ready & Scalable
- Data & models stored on Google Cloud Storage (GCS)
- Auto-download model when missing
- Efficient `.parquet` storage (28M+ rows)
- Streamlit Cloud or GCP Cloud Run deployable

---

## 📂 Project Structure
```
UK-RealEstate-Analytics/
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 01b_data_preparation.ipynb
│   ├── 02_Feature_Engineering_*.ipynb
│   ├── 03_Modeling_*.ipynb
├── app/
│   └── streamlit_macro_dashboard.py   # Streamlit app with SHAP + Simulation
├── data/
│   └── merged_real_estate_macro.parquet
├── models/
│   ├── CatBoost_model.cbm
│   ├── XGBoost_model.json
│   ├── LightGBM_model.pkl
│   └── feature_names.json
├── requirements.txt
├── Dockerfile (optional)
└── README.md
```

---

## ⚙️ Requirements
- Python 3.8+
- Google Cloud SDK (if using GCS)
- Install with:
```bash
pip install -r requirements.txt
```

---

## 💻 How to Run
```bash
# 1. Clone the repo
https://github.com/Boothill2001/UK-RealEstate-Analytics.git

# 2. Move to app directory
cd app

# 3. Run Streamlit app
streamlit run streamlit_macro_dashboard.py
```

---

## 📸 App Preview (coming soon)
- SHAP explainability bar chart
- Price vs. macroeconomic trends
- Batch prediction & scenario sliders

---

## 🧠 Who Is This For?
- Aspiring Data Scientists (especially Economic / Policy-focused)
- Researchers studying housing & macroeconomic dynamics
- ML Engineers looking for GCP-integrated E2E pipelines

---

## 🔧 Upcoming Features
- [ ] Time Series Forecasting (Prophet, ARIMA, LSTM)
- [ ] MLflow integration (for experiment tracking)
- [ ] Economic Drift Monitoring with Evidently
- [ ] Streamlit Cloud / GCP Cloud Run deploy
- [ ] LIME & SHAP waterfall visualization

---

## 📝 Contributions
Open issues or submit pull requests – happy to collaborate!

## 📫 Contact
- Email: boothill2001.grant@gmail.com
- GitHub: [@Boothill2001](https://github.com/Boothill2001)
- LinkedIn: *(coming soon – link here)*

---

Made with 💡, GCS, and many cups of ☕ by **Boothill2001**
