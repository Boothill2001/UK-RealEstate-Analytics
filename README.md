# 🏡 UK Real Estate Analytics + Economic Modeling + Hybrid Forecasting

Welcome to the most advanced **Real Estate + Macro-Economic Insight System** for the UK 🇬🇧!  
This project goes beyond prediction — it empowers analysts, investors, and policymakers with forecasting, simulation, and explainability tools that combine housing data with economic indicators.

---

## 📑 Project Overview

This project aims to:
- Analyze UK real estate transaction data (1995–2023).
- Integrate macroeconomic indicators (GDP, CPI, interest rate, FX, etc.).
- Predict property prices using state-of-the-art ML and Time Series models.
- Explain predictions with SHAP/LIME.
- Simulate economic scenarios: "What if inflation increases by 2%?"
- Deploy a full-stack Streamlit app with cloud-hosted models & monitoring.

---

## 🚀 Key Features

### 📊 Interactive Dashboard (Streamlit)
- Filter by year and macroeconomic variables.
- Visualize trends, distributions, correlations.
- Run predictive simulations with custom macro inputs.
- Batch prediction via uploaded CSVs.

### 🔢 Machine Learning & Time Series Models
- Machine Learning:
  - ✅ CatBoost, XGBoost, LightGBM
- Time Series Forecasting:
  - ✅ Prophet (monthly forecast)
  - ✅ LSTM Sequence Modeling
- Hybrid Forecasting:
  - ✅ Prophet + LSTM hybrid evaluated against 2023 actuals.
- SHAP explainability integrated (local + global).
- MAE/RMSE comparison dashboard for model evaluation.

### 🧠 Economic Intelligence
- Elasticity analysis (e.g., price sensitivity to GDP changes).
- Scenario simulation (interest rate hikes, recession modeling).
- Explainable AI with SHAP summary & waterfall plots.

### ☁️ Cloud-Ready & Scalable
- Data and models stored on Google Cloud Storage (GCS).
- Auto-download models if missing.
- Efficient `.parquet` storage (28M+ rows).
- Deployable via Streamlit Cloud or GCP Cloud Run.

## 📂 Project Structure

| Path | Description |
|:-----|:------------|
| `notebooks/` | Jupyter notebooks for data exploration, feature engineering, modeling, forecasting. |
| ├── `01_data_exploration.ipynb` | Initial EDA on real estate data. |
| ├── `01b_data_preparation.ipynb` | Data cleaning and preprocessing. |
| ├── `02_Feature_Engineering_Sampling.ipynb` | Feature extraction on sampled dataset. |
| ├── `02b_Feature_Engineering_Full.ipynb` | Feature engineering on full dataset. |
| ├── `03_Modeling_Sample.ipynb` | Modeling with sample data. |
| ├── `03b_Modeling_Full.ipynb` | Full dataset modeling. |
| ├── `04a_forecasting_prophet_arima.ipynb` | Time series forecasting using Prophet and ARIMA. |
| ├── `04b_LSTM_forecasting.ipynb` | Deep learning forecasting with LSTM. |
| ├── `04c_LSTM_forecasting_clean.ipynb` | Cleaned and tuned LSTM model. |
| ├── `05_Forecast_Comparison.ipynb` | Comparison between forecasting models. |
| ├── `new_eda_macro_real_estate.ipynb` | EDA on merged real estate and macroeconomic data. |
| ├── `macro_merge_colab.ipynb` | Merge and preprocessing of macroeconomic data. |
| └── `streamlit_macro_dashboard.ipynb` | Build dashboard for macro-real estate data. |
| `app/` | Streamlit app source code. |
| ├── `streamlit_macro_dashboard.py` | Streamlit dashboard app file. |
| `data/` | Folder for processed datasets. |
| ├── `merged_real_estate_macro.parquet` | Cleaned and merged dataset for analysis. |
| `models/` | Trained machine learning models. |
| ├── `CatBoost_model.cbm` | CatBoost regression model. |
| ├── `XGBoost_model.json` | XGBoost regression model. |
| ├── `LightGBM_model.pkl` | LightGBM regression model. |
| └── `feature_names.json` | Feature names mapping. |
| `requirements.txt` | Python dependencies. |
| `Dockerfile (optional)` | Docker instructions for deployment. |
| `README.md` | Project documentation. |



## ⚙️ Requirements
- Python 3.8+
- Google Cloud SDK (if using GCS)
- Install with:
```bash
pip install -r requirements.txt
💻 How to Run
bash
Sao chép
Chỉnh sửa
# 1. Clone the repository
git clone https://github.com/Boothill2001/UK-RealEstate-Analytics.git

# 2. Move into app folder
cd app

# 3. Run the Streamlit dashboard
streamlit run streamlit_macro_dashboard.py
📸 App Preview (Coming soon)
SHAP global and local feature importance plots.

Price trends vs. macroeconomic factors.

Interactive simulation sliders for forecasting.

Batch prediction with uploaded datasets.

🧠 Who Is This For?
Aspiring Data Scientists (especially Economic / Policy-focused).

Researchers studying housing market dynamics and economic trends.

ML Engineers looking for full-cycle ML + Cloud deployment experience.

🔧 Upcoming Enhancements
 Time Series Forecasting (Hybrid Prophet + LSTM deeper analysis)

 MLflow integration for experiment tracking.

 Economic Drift Monitoring with Evidently.

 Streamlit Cloud and GCP Cloud Run deployment.

 SHAP & LIME detailed visualization dashboards.

📝 Contributions
Open issues or submit pull requests — happy to collaborate!

📫 Contact
📧 Email: boothill2001.grant@gmail.com

💻 GitHub: @Boothill2001

🔗 LinkedIn: (coming soon – link here)

Made with 💡, GCS, and many cups of ☕ by Boothill2001
