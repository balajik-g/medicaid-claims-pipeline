# medicaid-claims-pipeline

# Project Structure

medicaid-claims-pipeline/
│
├── data/
│   ├── raw/
│   ├── silver/
│   ├── gold/
│
├── notebooks/
│   ├── 01_bronze_to_silver_etl.py
│   ├── 02_silver_to_gold_etl.py
│   ├── 03_fraud_model_mlflow.py
│
├── api/
│   ├── main.py             # FastAPI scoring service
│   ├── test_api_predict.py # API test
│
├── tests/
│   ├── test_data_quality.py
│
├── scripts/
│   ├── generate_dummy_data.py
│
├── docs/
│   ├── schema_definitions.xlsx
│   ├── architecture_diagram.png
│   ├── README.md
│
├── requirements.txt
└── .gitignore



