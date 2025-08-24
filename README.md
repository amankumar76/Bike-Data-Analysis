# 🏍️ Bike Data Analysis with Pandas & Visualization

This repository contains an end-to-end **Exploratory Data Analysis (EDA)** of a bike dataset using **Python, Pandas, Matplotlib, and Seaborn**.

## 📊 Dataset
- File: `BIKE DETAILS.csv`
- Contains details about used bikes such as:
  - `name`, `year`, `selling_price`, `km_driven`, `seller_type`, `owner`, etc.

## 🚀 Analysis Questions
1. Read the dataset and display shape, columns, and first 10 rows.
2. Check for missing values and handle them.
3. Plot distribution of selling prices (histogram).
4. Bar plot of average selling price by seller type.
5. Average km_driven for each ownership type (bar plot).
6. Remove outliers in `km_driven` using IQR method.
7. Scatter plot of year vs. selling_price.
8. Convert seller_type into numeric using one-hot encoding.
9. Generate heatmap of correlation matrix.
10. Summarize findings.

## 🛠️ Tech Stack
- Python 3
- Pandas
- Matplotlib
- Seaborn

## 📂 Files
- `bike_analysis.ipynb` → Jupyter Notebook with code, outputs, and answers
- `bike_analysis.py` → Python script version
- `outputs/` → Visualization plots

## 📌 Findings
- **Year** strongly affects selling price (newer bikes are costlier).
- **Seller type** influences price (dealers list higher).
- **Ownership** impacts resale value (first owner bikes sell for more).
- **KM driven** reduces bike value.
- Outliers in `km_driven` were removed for better accuracy.
