# 📊 Research Project

## 🧩 Assessing the Impact of Energy Poverty on Human Development Index (HDI) and Aligning with SDG 7: A State-Wise Analysis

---

### 📌 Project Description
This research project investigates the **multidimensional nature of energy poverty** and its impact on human development across Indian states. Using data from **NFHS rounds (3, 4, and 5)** and socio-economic indicators, the study constructs a **Multidimensional Energy Poverty Index (MEPI)**, examines its effect on **Human Development Index (HDI)**, and explores alignment with **SDG 7 – Affordable and Clean Energy for All**.

The study applies **PCA, panel regression modeling, exploratory data analysis**, and **clustering techniques** to identify disparities and support data-driven energy policy recommendations.

---

### 🎯 Objectives

1. **Construct the Multidimensional Energy Poverty Index (MEPI):**  
   - Based on electricity and clean cooking fuel access  
   - Weighted using principal component analysis (PCA)

2. **Analyze the MEPI-HDI relationship:**  
   - Using **fixed-effects panel data regression**  
   - Controls: Female literacy, infant mortality, and wealth index

3. **Align trends with SDG 7 goals:**  
   - Track improvements in energy access vis-à-vis SDG 7 benchmarks

4. **Map regional disparities and clusters:**  
   - State-level **K-means clustering** of MEPI and HDI  
   - Identify vulnerable states needing policy priority

5. **Conduct Exploratory Data Analysis (EDA):**  
   - Visualize state-wise trends in energy poverty and human development  
   - Use heatmaps, time-series, and correlation graphs

---

### 📚 Data Sources

- **NFHS Rounds 3, 4, and 5** (2005–21): Access to electricity, clean cooking, sanitation, water  
- **HDI**: UNDP state-wise values (1990–2022)  
- **Socio-Economic Indicators**: Female literacy, IMR (Census, RBI, MOSPI)

---

### ⚙️ Methodology

1. **Data Preprocessing:**  
   - Pooled panel dataset of 29 states across three time points  
   - Standardized indicators for comparability

2. **Index Construction:**  
   - MEPI based on PCA (access to electricity, clean cooking)  
   - Higher MEPI → Higher energy poverty

3. **EDA and Visualizations:**  
   - Heatmaps, bar plots, temporal line graphs  
   - Insights into MEPI-HDI correlations

4. **Panel Regression Modeling:**  
   - Fixed-effects regression: HDI ~ MEPI + controls  
   - Tested statistical significance and robustness

5. **Clustering Analysis:**  
   - K-means clustering on MEPI-HDI matrix  
   - Identified low-HDI, high-MEPI states needing intervention

---

### ✅ Project Status: Completed

- [x] Data cleaned and merged from NFHS, UNDP, Census  
- [x] MEPI constructed and visualized  
- [x] Regression model finalized and interpreted  
- [x] State clusters identified and mapped  
- [x] Policy insights derived from statistical results

---

### 📈 Key Findings

- A **0.1 unit increase in MEPI** leads to a **7.8% decline in HDI** (statistically significant)  
- Impact of energy poverty **weakened in 2015**, reflecting effects of schemes like **Ujjwala**  
- **Cluster 3** states (e.g., Bihar, Odisha) suffer both **high energy poverty and low HDI**  
- **Female literacy and wealth index** emerged as strong complementary factors

---

### 💡 Policy Recommendations

- **Solar microgrid deployments** in low-HDI states  
- **Targeted LPG and appliance subsidies** for rural/tribal belts  
- **Use MEPI in SDG 7 dashboards** to track progress and trigger alerts

---

### 🗂️ Project Structure

Research-Project/
├── data/ # Raw and processed datasets
│ ├── NFHS/ # NFHS-3, 4, 5 data
│ ├── HDI/ # UNDP HDI values
│ └── external/ # IMR, literacy, GDP data
│
├── src/ # Scripts and notebooks
│ ├── preprocessing/ # Data cleaning and merging
│ ├── analysis/ # MEPI calculation, PCA, regression
│ └── visualization/ # Graphs, heatmaps, cluster maps
│
├── visualizations/ # Output images for reports
│ ├── MEPI/ # State-wise maps and trends
│ ├── HDI/ # Line and bar plots
│ └── correlations/ # Scatterplots and clustering visuals
│
├── reports/
│ ├── interim/ # Progress updates
│ ├── final/ # Final paper and presentations
│ └── supplementary/ # References, appendices
│
├── README.md # This file
├── LICENSE
└── requirements.txt # Required Python packages
