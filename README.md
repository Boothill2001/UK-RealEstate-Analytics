# 🏡 UK Real Estate Analytics

## 📑 Project Overview
This project aims to analyze real estate transaction data from the UK to uncover insights and predict property prices. The data is obtained from the UK Land Registry and processed using Python. The final output is a consolidated and cleaned dataset ready for analysis and modeling.

## 🚀 Key Features
1. **Data Preprocessing:**
   - Handles missing values, inconsistent data types, and outliers.
   - Efficient memory management for large datasets (28 million rows).

2. **Feature Engineering:**
   - Extracts temporal features: Year, Month, Quarter.
   - Derives regional information from postal codes.

3. **Data Consolidation:**
   - Merges large data chunks from Google Cloud Storage (GCS) into a single file.
   - Saves the consolidated file back to GCS for future analysis.

4. **Exploratory Data Analysis (EDA):**
   - Visualizes property price distribution and type frequency.
   - Analyzes temporal trends and regional variations.

## 📂 Project Structure
```
UK-RealEstate-Analytics/
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 01b_data_preparation.ipynb
├── scripts/
│   └── 02_data_preparation.py
├── data/
│   ├── raw/
│   └── processed/
├── README.md
└── requirements.txt
```

## 🛠️ Requirements
- Python 3.8+
- Google Cloud SDK
- Libraries:
  - pandas
  - google-cloud-storage
  - matplotlib
  - seaborn

## 💻 Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Boothill2001/UK-RealEstate-Analytics.git
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the data preparation script:
   ```bash
   python scripts/02_data_preparation.py
   ```

## 📝 Contributions
Feel free to contribute to this project by opening issues and pull requests.

## 📧 Contact
For any inquiries, please contact: boothill2001.grant@gmail.com

