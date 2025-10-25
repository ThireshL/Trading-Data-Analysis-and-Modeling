# Trading-Data-Analysis-and-Modeling
# Trading Data Analysis and Modeling

This Jupyter Notebook provides a complete workflow for reading, cleaning, analyzing, and preparing trading data for machine learning modeling using **pandas**, **seaborn**, and **scikit-learn**. It automates exploratory data analysis (EDA), feature engineering, outlier detection, and model preparation for structured financial datasets.

---

## 1. Overview

The notebook performs an end-to-end analysis on trade-level data spanning multiple instruments and venues. It is designed to handle large datasets efficiently and extract insights from key variables such as trade volume, price dynamics, and instrument behavior.

**Main objectives:**
- Combine multiple CSV trade files into a master dataset  
- Clean and preprocess the data for anomalies and inconsistencies  
- Engineer analytical features (trade amount, time dimensions)  
- Visualize trading trends and detect outliers  
- Identify dominant venues and instruments  
- Prepare data for predictive modeling  

---

## 2. Project Workflow

| Step | Description |
|------|-------------|
| **Step 1 – Data Cleaning** | Handles missing values, converts data types, and removes duplicates |
| **Step 2 – Feature Engineering** | Creates new columns such as trade amount, day/hour, and weekday |
| **Step 3 – EDA** | Performs visual and descriptive analysis to identify trade patterns |
| **Step 4 – Outlier Detection** | Uses both visual and statistical (IQR) methods to detect and remove extreme values |
| **Step 5 – Venue & Instrument Analysis** | Highlights which venues and instruments dominate total trade amounts |
| **Step 6 – Model Preparation** | Encodes categorical features, scales numeric ones, and prepares training/testing splits |

---

## 3. Results Summary
- **Top Trading Venue:** HAND  
- **Dominant Instrument:** US67066G1040  
- **Notable Trading Pattern:** Spikes in activity observed around **9 AM UTC**  
- **Other Key Instruments:** US0079031078, US0231351067  
- **Total Processed Records:** ~815,000 (after cleaning)  

---

## 4. Requirements

Ensure the following Python packages are installed:
