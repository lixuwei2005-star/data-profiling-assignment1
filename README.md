# Assignment 1: Data Profiling (EDA) Report

## Group Members

| Name | Matric No. |
|---|---|
| HU XIAOZHANG | A214111 |
| CHI YULONG | A213955 |
| LI XUWEI | A214014 |

## Scenario

This project profiles a healthcare dataset of hospital encounters for patients with diabetes. The data contains missing values, outliers, invalid values, and possible privacy and bias risks. The notebook identifies where these data quality problems occur, how serious they are, and how they can be handled before further analysis.

## Data Source

- **Source:** Kaggle - Diabetes dataset
- **File:** `diabetic_data.csv` (101,766 rows, 50 columns)
- **URL:** https://www.kaggle.com/datasets/brandao/diabetes?select=diabetic_data.csv
- **How obtained:** downloaded manually from Kaggle as a CSV file

## Files

- `Assignment_1_Data_Profiling.ipynb` - the main notebook (scenario, data profiling, issue handling, charts, PII and bias risks, conclusion)

## How to Run

1. Download `diabetic_data.csv` from the Kaggle link above.
2. Open `Assignment_1_Data_Profiling.ipynb` in Google Colab.
3. Upload `diabetic_data.csv` to the Colab session so it is located at `/content/diabetic_data.csv`.
4. Click **Runtime → Run all** to run the notebook from top to bottom.

Required libraries: `pandas`, `matplotlib` (pre-installed in Google Colab).
