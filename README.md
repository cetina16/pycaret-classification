# Marketing ML Training Pipeline

This project contains a Python script designed to perform machine learning model training using the [PyCaret](https://pycaret.org/) library.

The pipeline is prepared for preprocessing, model comparison, and analysis in a streamlined way.

---


## ⚙Features

- Loads a CSV dataset with custom data types for object columns
- Uses `PyCaret` to quickly profile and compare models
- Handles marketing/industry features such as:
  - `country`
  - `industry_claim`, `industry_other`, `industry_surveys`, etc.
  - `marketing_intent`, `marketing_team`, `marketing_use_case`
  - Time-based features: `sign_up_time`, `first_camera_time`, etc.

---

## Getting Started

### 1. Install Requirements
```bash
pip install pycaret pandas scikit-learn matplotlib seaborn
```

### 2. Add Dataset
Place your dataset (CSV file) in the same folder as the script. 

### 3. Run the Pipeline
```bash
python pipeline_train.py
```

---
