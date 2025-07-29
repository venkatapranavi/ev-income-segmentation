# EV Market Segmentation Report (Income_Based)

This project focuses on segmenting potential EV customers based on their income. The goal is to help an EV company understand different income groups and develop targeted strategies.

## Team Members
- Pranavi
- Saranya

## Dataset
- File Name: `income.xlsx`
- Features: Age, Profession, Marital Status, Education, Salary, Wife Salary, Total Salary, Car Make, Car Price

## Tools Used
- Python
- Google Colab (Jupyter Notebook)
- Libraries: pandas, matplotlib, seaborn, scikit-learn

## Methodology
1. Loaded the dataset from Excel
2. Focused on 'Total Salary' for income-based segmentation
3. Used Elbow Method to determine number of clusters
4. Applied KMeans clustering to group customers
5. Created visualizations to interpret the clusters

## Results
- Cluster 0: Lower income (₹8–12 lakhs) – likely budget EV buyers
- Cluster 1: Middle income (₹13–18 lakhs) – suitable for mid-range EVs
- Cluster 2: High income (₹20–26 lakhs) – suitable for premium EVs

## Recommendation
- Offer affordable EVs to Cluster 0
- Provide value-for-money EVs to Cluster 1
- Target Cluster 2 with premium and feature-rich EV models

## Report
Refer to `EV_Segmentation_Report.pdf` for full analysis.
