# Capstone Project: Reasons for Crimes in India and Measures to Prevent Them

## Overview

This project investigates the underlying causes of crimes in Indian districts by analyzing their relationship with various socioeconomic and systemic indicators. The aim is to detect patterns between different types of crimes (violent, property, cyber) and factors like poverty, unemployment, literacy, and GDP per capita. By identifying these relationships, the project will propose data-driven preventive measures and guide policy recommendations.

## Objective

* Explore how crime rates across India are influenced by external factors such as economic disparity, literacy, unemployment, and systemic inefficiencies.
* Use unsupervised learning techniques to uncover patterns and cluster regions with similar crime dynamics.
* Predict crime rates and identify actionable insights to support crime prevention strategies.

## Dataset Source

The primary dataset comes from Kaggle:

* [Crime and Socioeconomic Indicators Dataset: India](https://www.kaggle.com/datasets/bhaskarmishra44796/crime-and-socioeconomic-indicators-dataset-india)
* Contains 700 district-year records (2018–2023), including:

  * Population
  * GDP per Capita
  * Literacy Rate (%)
  * Poverty Rate (%)
  * Unemployment Rate (%)
  * Crime statistics (Violent, Property, Cyber, Total Crimes, Crime Rate per 100,000)

## Additional Data Needs

To enhance the analysis, additional datasets may be sourced and merged:

* Civic infrastructure (e.g., traffic congestion, urbanization rates)
* Judicial efficiency (e.g., average sentence length, conviction rates)
* Local law enforcement or policy initiatives
* District-wise behavioral or mental health stress indicators
* Wikipedia and government portals like NCRB, MOSPI

## Techniques Used

### 1. Data Preparation

* Data cleaning, merging, and transformation
* Handling missing values and outliers

### 2. Exploratory Data Analysis (EDA)

* Correlation matrix & pair plotting
* Feature engineering for normalized comparisons (e.g., crime per capita)

### 3. Unsupervised Learning

* **Principal Component Analysis (PCA)**: Reduce dimensionality and highlight influential variables.
* **K-Means Clustering**: Group similar districts based on socioeconomic and crime factors.
* **DBSCAN**: Identify irregular clusters and outliers in crime patterns.

## Expected Outcome

* Identification of the most influential factors contributing to crime
* Clustered profile of Indian districts with similar crime drivers
* Region-specific recommendations for crime prevention
* Visualizations to support public awareness and policy intervention

## Tools and Libraries

* Python (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn)
* Jupyter Notebook for analysis

## Next Steps

1. Perform deeper feature engineering (e.g., standardizing district names)
2. Integrate external datasets for civic stress, law enforcement, and judiciary
3. Explore supervised models to predict crime levels (optional)

---

*This capstone is part of the AI/ML Certificate Program and focuses on applying real-world data analysis and clustering techniques to a socially relevant domain.*
