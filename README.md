# 🍷 EDA of Wine Quality Dataset (R)

**Project Type:** Exploratory Data Analysis  
**Tools:** R, ggplot2, dplyr, tidyr  
**Dataset:** Red Wine Quality Data (1,599 records, 11 chemical properties + expert quality ratings)

---

## 📌 Project Overview

This project explores the chemical properties of red wine and how they relate to wine quality, using **Exploratory Data Analysis (EDA)** techniques in R. The dataset includes 11 physicochemical variables (e.g., acidity, pH, alcohol) and a quality score rated by wine experts.

EDA is a crucial step in the data analysis pipeline, helping uncover relationships, detect outliers or anomalies, and guide future modeling efforts. This project includes:
- Univariate, bivariate, and multivariate visual analysis
- Distribution analysis
- Detection of outliers and correlations
- Visual and statistical summaries using R

---

## 📎 Acknowledgments

This project was completed as part of the **Udacity Data Analyst Nanodegree** program.  
The dataset was sourced from the **[UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)** and is made available under public license for educational and research use.

---


## ⚖️ License

This repository is provided for educational purposes only under the [MIT License](LICENSE).

## 🎯 Why This Project Matters

EDA is not just about making plots — it's about making sense of data before you build models. It helps:
- Catch errors or inconsistencies in raw data
- Identify trends and variable relationships
- Develop hypotheses for predictive modeling
- Confirm or challenge assumptions before deeper statistical analysis

---

## 🧪 Dataset Details

- 📁 Source: [UCI Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)
- 🍷 1,599 observations of red wine samples
- 📐 11 chemical properties per sample:
  - fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol
- 🏷️ Quality rating from 0 (very poor) to 10 (excellent) by at least 3 wine experts

Each row in the dataset represents a unique wine sample, evaluated based on its physicochemical makeup and expert quality rating.

---

## 🧰 Tools & Techniques Used

- **R Language**
  - `ggplot2` for data visualization
  - `dplyr` and `tidyr` for data cleaning and transformation
  - Summary statistics and boxplots for outlier detection
  - Correlation analysis and heatmaps

---

## 📈 Key Insights

- **Alcohol content** was positively correlated with higher wine quality ratings.
- **Volatile acidity** and **total sulfur dioxide** were negatively associated with quality.
- Outliers were found in **residual sugar** and **sulphates**, which could affect modeling.
- Several variables showed strong interrelationships (e.g., citric acid and pH).

---

## 📂 Project Structure
    eda-wine-quality-r/
    ├── data/
    │   └── wineQualityReds.csv
    ├── scripts/
    │   └── RedWineAnalysis_Knit.html
    │   └── RedWineAnalysis_RMD.rmd
    └── README.md
