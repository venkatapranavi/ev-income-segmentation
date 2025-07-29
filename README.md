

# EV Market Segmentation - Income-Based Analysis

This project explores income-based segmentation of potential Electric Vehicle (EV) customers in India. The goal is to help an EV manufacturing company better understand its target audience and design products and strategies that align with different income groups.

## Team Members

* Pranavi
* Saranya

## Dataset Description

* File used: `income.xlsx`
* The dataset includes the following columns:

  * Age, Profession, Marital Status, Education
  * Number of Dependents
  * Personal Loan, House Loan, Wife Working
  * Salary, Wife Salary, Total Salary
  * Vehicle Make, Vehicle Price

## Tools and Technologies

* Platform: Google Colab
* Programming Language: Python
* Libraries:

  * pandas
  * matplotlib
  * seaborn
  * scikit-learn

## Process Overview

1. Loaded and cleaned the dataset.
2. Focused on the 'Total Salary' column for segmentation.
3. Used the Elbow Method to determine the optimal number of clusters.
4. Applied KMeans clustering.
5. Visualized the clusters and interpreted their characteristics.

## Results

Three distinct income segments were identified:

* Cluster 0: ₹8–12 lakhs - budget-sensitive customers
* Cluster 1: ₹13–18 lakhs - likely to purchase mid-range EVs
* Cluster 2: ₹20–26 lakhs - premium buyers with higher purchasing power

These clusters can be used to guide EV model development, pricing, and marketing strategies.

## Business Recommendation

* Target Cluster 0 with affordable EVs and EMI options.
* Offer Cluster 1 mid-range EVs with strong value-for-money features.
* Market premium, performance-focused EVs to Cluster 2.

## How to Run

1. Open the notebook file `EV_Income_Clustering.ipynb` in Google Colab.
2. Upload the dataset file `income.xlsx`.
3. Run all cells to execute the segmentation and view results.

## Report

Refer to the file `EV Market Segmentation Report(Income_Based).pdf` in this repository for a complete analysis.

