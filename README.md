altscore-ai/
├── data/                  # Raw and processed datasets (raw data gitignored)
├── notebooks/             # Step-by-step analysis & model development
│   ├── 01_eda.ipynb                     # Exploratory Data Analysis
│   ├── 02_feature_engineering.ipynb     # Alt-data transformations & aggregation
│   ├── 03_woe_iv_scorecard.ipynb        # Weight of Evidence & Information Value binning
│   ├── 04_modeling.ipynb                # Logistic Regression vs. XGBoost training
│   ├── 05_shap_explainability.ipynb     # Model interpretability & adverse action reasons
│   └── 06_business_optimization.ipynb   # Profitability thresholds & score scaling
├── src/                   # Reusable Python modules & feature extraction logic
├── app/                   # Interactive Streamlit credit decisioning application
├── dashboard/             # Power BI dashboard files (.pbix) & visual previews
└── README.md              # Project overview & documentation
