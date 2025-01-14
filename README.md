# KIAM Week 4 - Rossmann Pharmaceutical Stores

## Overview
This repository contains an exploratory data analysis (EDA) report on sales data from Rossmann Pharmaceutical Stores. The purpose of this analysis is to summarize key characteristics of the dataset, visualize distributions, and uncover trends across various categories.

---

## Data Overview
The dataset consists of three files:
1. **Store**: Contains information about the stores.
2. **Training Set**: Contains historical sales data for training models.
3. **Test Set**: Contains future data for testing predictions.

These datasets include features related to sales, store attributes, and customer behavior.

---

## Libraries Used
The following Python libraries were used for data manipulation, analysis, and visualization:

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib**: For static, animated, and interactive visualizations.
- **Seaborn**: For statistical data visualization.

---

## Instructions

### 1. Preprocess the Data
Convert and clean the dataset using the provided script:
```bash
python src/txt_to_csv_clean.py
```

### 2. Perform Exploratory Data Analysis
Run the Jupyter Notebook to perform the EDA:
```bash
jupyter notebook EDA_analysis.ipynb
```

---

## Results
Key insights and visualizations from the analysis include:
- Trends in sales over time.
- Seasonal patterns and their impact on sales.
- Customer behaviors and store-specific factors contributing to sales performance.

---

## Repository Structure
```
KIAM-Week-4-Rossmann/
│
├── data/                 # Dataset files
│   ├── store.csv
│   ├── train.csv
│   ├── test.csv
│
├── src/                  # Scripts for preprocessing and analysis
│   ├── txt_to_csv_clean.py
│
├── notebooks/            # Jupyter notebooks for EDA and modeling
│   ├── EDA_analysis.ipynb
│
└── README.md             # Project documentation
```

---

## Requirements
Ensure you have the following installed:
- Python 3.9+
- Jupyter Notebook
- Libraries listed in `requirements.txt` (install them with `pip install -r requirements.txt`)

---

## Contact
For any questions or feedback, feel free to reach out.
