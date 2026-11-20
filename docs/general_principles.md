## **General Principles**

- **Naming Conventions**: Use snake_case, with lowercase letters and underscores (`_`) to separate words.
- **Language**: Use English for all names.
- **Avoid Reserved Words**: Do not use SQL reserved words as object names.

## **Table Naming Conventions**

nyc_taxi_dwh/
├── README.md
├── DECISIONS.md
├── RUNBOOK.md
├── .gitignore              # data/, .env, __pycache__/
├── docs/
│   ├── naming_conventions.md
│   ├── data_catalog.md
│   └── diagrams/
├── ingestion/              # Python package
│   ├── download_tlc.py
│   └── download_weather.py
├── sql/
│   ├── ddl/bronze/  ddl/silver/  ddl/gold/
│   └── procs/
├── tests/
└── data/raw/               # not committed
