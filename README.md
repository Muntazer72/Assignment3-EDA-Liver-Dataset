# PythonAI7-EDA-Liver-Assignment03

This repository contains the Exploratory Data Analysis (EDA) project for **Assignment 3** of the **Python with AI (7th Batch)** course. The analysis focuses on the Indian Liver Patient Dataset (ILPD) to gain insights into the attributes related to liver health and disease diagnosis.

## 📁 Dataset
- **Name**: Indian Liver Patient Dataset (ILPD)
- **Source**: UCI Machine Learning Repository
- **Attributes**: 10 features + target label
- **Target**: `Liver_Disease` (1 = Patient, 2 = Healthy)

## 🔍 EDA Tasks Performed

- Loaded and inspected dataset shape, types, and missing values.
- Renamed columns for better readability.
- Filled missing values using the median strategy.
- Generated summary statistics (`describe()`).
- Visualized distributions using:
  - Histograms
  - Countplots (Gender & Target Class)
  - Correlation heatmap
  - Boxplots for outlier detection
- Detected and removed outliers using IQR method.
- Final dataset shape after cleaning.

## 📊 Libraries Used

- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `warnings`
